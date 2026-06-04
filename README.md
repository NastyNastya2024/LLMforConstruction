# Structora AI — маркетинговый сайт

Локальный AI для строительных компаний. Статический многостраничный сайт в стиле SaaS-дашборда.

## Страницы

| Файл | Содержание |
|------|------------|
| `index.html` | Главная: hero, ценность, решения, архитектура, CTA |
| `local-ai.html` | Что такое локальный AI (on-premise) |
| `product.html` | Описание платформы и эффект для бизнеса |

## Локальный запуск

```bash
cd /Users/a1/Documents/GitHub/LLMforConstruction
python3 -m http.server 8080
```

Откройте [http://localhost:8080](http://localhost:8080).

## Структура

```
css/styles.css   — дизайн-система (карточки, навигация, метрики)
js/main.js       — мобильное меню и плавная прокрутка
index.html
local-ai.html
product.html
```

## Деплой

Сайт можно разместить на GitHub Pages, Netlify или любом статическом хостинге — достаточно загрузить корень репозитория.

# Lina Date 💗 — Telegram Mini App

Готовый одностраничный Mini App по логике пяти скриншотов.

## Что внутри
- 5 экранов: приглашение → подтверждение → дата/время → еда → билет.
- Работает в Telegram WebApp через `telegram-web-app.js`.
- Выбор даты, времени и еды переносится на финальный билет.
- В `assets/` лежат исходные изображения из предоставленных скриншотов.

## Важно про изображения
Сейчас используются изображения из присланных скриншотов как временные ассеты. Если есть оригинальные фотографии котика/девушки/еды/билета, их лучше заменить в `assets/` — интерфейс останется тем же.

## Быстрый запуск
Можно открыть `index.html` локально для проверки дизайна, но Telegram Mini App требует HTTPS-URL. Для BotFather нужен публичный адрес вроде:
`https://USERNAME.github.io/lina-date/`

## GitHub Pages
1. Создай новый GitHub repository, например `lina-date`.
2. Загрузите `index.html`, папку `assets` и этот README.
3. GitHub → Settings → Pages → Deploy from a branch → `main` → `/root`.
4. После публикации получишь HTTPS URL.
5. В @BotFather: `/mybots` → Lina Date → Bot Settings → Configure Mini App → Enable Mini App → отправь URL.

## Команда бота
`/start` можно использовать как точку входа. Для открытия Mini App в меню BotFather можно настроить Menu Button.

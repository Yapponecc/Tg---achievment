# TG Achievement Widget (GitHub Pages Ready)

Файлы уже подготовлены для публикации через GitHub Pages.

## Что важно
- Главная страница: `index.html`
- Отключение Jekyll: `.nojekyll`

## Что поменять под себя
В `index.html` найди блок `const widgetData = { ... }` и замени:
- `title` - название твоего TG
- `handle` - `@username`
- `telegramUrl` - ссылка `https://t.me/username`
- `serverLabel` - подпись перед `@username`

## Публикация на GitHub Pages
1. Загрузи `index.html` и `.nojekyll` в корень репозитория.
2. Открой `Settings -> Pages`.
3. Выбери:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - `Folder`: `/ (root)`
4. Нажми `Save`.
5. Через 1-3 минуты сайт будет доступен по ссылке:
   `https://<your-username>.github.io/<repo-name>/`

# Місто Світла — Telegram Mini App церкви

- Корень репозитория — само приложение (GitHub Pages): `index.html`, `devs.js`, `guide.js`, `en.js`, папки `bible/`, `books/`, `cards/`. Адрес: https://anubisshaman.github.io/misto-svitla/
- `server/` — Google Apps Script (`Code.gs`, `appsscript.json`). Секретов в коде нет: BOT_TOKEN, APP_URL, WEBAPP_URL, ADMIN_IDS лежат в Script properties.
- `tools/test-gs.js` — тесты сервера: `node tools/test-gs.js` должен напечатать `ALL GOOD`.
- Бот: @svitla_misto_bot. В `index.html` есть `var CONFIG={API_URL:'…/exec',BOT_USERNAME:'svitla_misto_bot'}` — не стирать.
- Языки интерфейса: украинский, русский, английский (`x(uk,ru,en)`).
- После изменения `server/Code.gs`: вставить в Apps Script и сделать «Управление развертываниями → Новая версия».
- Владелец общается по-русски, коротко и просто.

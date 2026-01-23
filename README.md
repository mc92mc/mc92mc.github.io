Рабочая папка: `pages`:
```sh
cd pages
```

Развернуть локальный сервер:
```sh
uv run mkdocs serve --livereload
```
`--livereload` - для автоматического обновления страницы при изменении файлов.


Отправить изменения на GitHub Pages:
```sh
uv run mkdocs gh-deploy
```
`gh-deploy` — команда, которая отправляет содержимое папки `site` на GitHub в ветку `gh-pages` для публикации на GitHub Pages.
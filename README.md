# mycardpage
My business card web-page for telegram

## Как выложить проект на GitHub

1. Создайте пустой репозиторий на GitHub (без README/License), например `mycardpage`.
2. Подключите удалённый репозиторий:
   ```bash
   git remote add origin https://github.com/<ваш-логин>/<имя-репозитория>.git
   ```
3. Закоммитьте и отправьте код:
   ```bash
   git add .
   git commit -m "Initial commit"
   git push -u origin work
   ```
   Если хотите пушить ветку `main`, сначала создайте её: `git checkout -b main`.
4. (Опционально) Включите GitHub Pages для публикации статического сайта:
   - В настройках репозитория откройте **Settings → Pages**.
   - В разделе **Branch** выберите ветку (`main` или другую) и папку `/root`.
   - Сохраните — через пару минут сайт будет доступен по выданной ссылке.

После этого любые новые изменения коммитьте и пушьте той же командой `git push`.

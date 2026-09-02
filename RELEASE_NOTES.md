# GamesTrack 0.2.1

## Русский

- Добавлено автономное нативное обновление Android напрямую из GitHub Releases.
- Новая версия проверяется автоматически раз в сутки или вручную из профиля.
- APK загружается внутри приложения, проверяется по SHA-256 и передаётся системному установщику Android.
- Обновлятор не зависит от API и веб-интерфейса GamesTrack и продолжает работать при сбое сервера.
- В публичный репозиторий добавлена расширенная галерея каталога, фильтров, напоминаний, личного календаря, коллекции, экспорта и галереи игры.
- Кнопки поддержки и Telegram заменены фирменными SVG из оформления svllvsxprod.

### Включено из 0.2.0

- Полная локализация сайта и Android-приложения на русский и английский языки.
- Переключатель языка с сохранением выбора.
- Локализованные авторизация, уведомления, системные сообщения и экспорт.
- PDF сортирует игры от самой высокой личной оценки к самой низкой; неоценённые игры идут в конце.
- Исправлено снятие отслеживания отдельной платформы: отметка больше не возвращается после синхронизации или перезапуска.
- Улучшена доступность элементов поиска и фильтров.

## English

- Added a native, backend-independent Android updater powered directly by GitHub Releases.
- Checks automatically once per day or manually from Profile.
- Downloads the APK in-app, verifies its SHA-256 digest, and hands it to the Android system installer.
- The updater remains usable if the GamesTrack API or web interface is unavailable.
- Expanded the public screenshot gallery to cover the catalog, filters, reminders, personal calendar, collection, exports, and game gallery.
- Replaced support and Telegram buttons with the branded svllvsxprod SVG artwork.

### Included from 0.2.0

- Full Russian and English localization for the website and Android app.
- Persistent language switcher.
- Localized authentication, notifications, system messages, and exports.
- PDF exports are sorted from the highest personal rating to the lowest; unrated games are listed last.
- Fixed platform reminder removal so stale synchronization can no longer restore an unchecked platform.
- Improved accessibility labels for search and catalog filters.

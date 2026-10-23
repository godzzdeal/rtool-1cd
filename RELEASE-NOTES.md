# rTool 1CD 1.1.1-beta

**Бета-версия для Windows x64**

Формат базы: **8.3.8.0**

## Скачать

- **[Установщик Windows x64](https://github.com/godzzdeal/rtool-1cd/releases/download/1.1.1-beta/rTool.1CD_1.1.1-beta_x64-setup.exe)**.
- [Контрольная сумма SHA-256](https://github.com/godzzdeal/rtool-1cd/releases/download/1.1.1-beta/rTool.1CD_1.1.1-beta_x64-setup.exe.sha256).

- **[CLI для Windows x64](https://github.com/godzzdeal/rtool-1cd/releases/download/1.1.1-beta/rtool-cli-1.1.1-beta-windows-x64.zip)** — распакуйте архив целиком и запустите `rtool-cli.exe`.
- [SHA-256 архива CLI](https://github.com/godzzdeal/rtool-1cd/releases/download/1.1.1-beta/rtool-cli-1.1.1-beta-windows-x64.zip.sha256).

## В этом выпуске

- Исправлена задержка при применении изменений в больших базах.
- Исправлены пропуски связей таблиц при работе с большими базами.
- Добавлен прогресс длительных операций и этапов сохранения.
- Добавлен журнал операций и ошибок. Папка журнала открывается через меню «Инструменты».

## CLI

Таблицы и индексы, вкладки, отбор по имени и разделу, поиск по значениям. Редактирование полей, добавление и удаление записей, общий список правок с отменой.

- **Tab / Shift+Tab** — дополнение путей в `/open`, `/save` и форме сохранения. Каталоги и файлы .1CD, пути с пробелами и кириллицей.
- **Ctrl+V / Shift+Insert** — вставка текста из буфера Windows.
- Новый стартовый экран с логотипом и подписью **by godzzdeal**.
- **F10** — форматы значений: HEX, UUID 1С, GUID и другие, для типа или отдельного поля.
- **Ctrl+S** — сохранить копию; **Ctrl+Shift+S** или `/save-current` — сохранить в открытую базу с подтверждением и резервной копией.
- **Ctrl+W** — закрыть вкладку; после последней открывается каталог.
- Длительные операции показывают текущий этап, процент, прошедшее время и предыдущие этапы.

Открыть базу: `/open "путь"`. Справка: `/help`. Папка `icu` должна оставаться рядом с `rtool-cli.exe`. WebView2 для CLI не требуется.

[Скриншоты CLI](https://github.com/godzzdeal/rtool-1cd#cli)

## Установка

Запустите установщик. Приложение устанавливается для текущего пользователя; недостающие компоненты будут предложены при установке.

Официальные страницы для ручной установки компонентов:

- [Microsoft Visual C++ 2010 SP1 x64](https://www.microsoft.com/en-us/download/details.aspx?id=26999) — файл **vcredist_x64.exe**.
- [Microsoft WebView2 Runtime](https://developer.microsoft.com/en-us/microsoft-edge/webview2/#download-section) — **Evergreen Standalone Installer, x64**.

Установщик не подписан.

> [!IMPORTANT]
> Перед редактированием закройте базу в 1С и сделайте резервную копию. Редактируйте тестовую копию базы.

[Сообщить об ошибке](https://github.com/godzzdeal/rtool-1cd/issues)

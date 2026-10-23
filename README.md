<h1 align="center">rTool 1CD</h1>

<p align="center">Просмотр и редактирование файловых баз 1С</p>

<p align="center">
  <img src="https://img.shields.io/badge/Windows-x64-0078D4?style=flat-square" alt="Windows x64">
  <img src="https://img.shields.io/badge/версия-1.1.1--beta-2563EB?style=flat-square" alt="Версия 1.1.1-beta">
</p>

<p align="center">
  <a href="https://v2.tauri.app/"><img src="https://img.shields.io/badge/Tauri-2-FFC131?style=flat-square&amp;logo=tauri&amp;logoColor=white" alt="Tauri 2"></a>
  <a href="https://react.dev/"><img src="https://img.shields.io/badge/React-19-61DAFB?style=flat-square&amp;logo=react&amp;logoColor=white" alt="React 19"></a>
  <a href="https://www.rust-lang.org/"><img src="https://img.shields.io/badge/Rust-000000?style=flat-square&amp;logo=rust&amp;logoColor=white" alt="Rust"></a>
  <a href="https://tailwindcss.com/"><img src="https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?style=flat-square&amp;logo=tailwindcss&amp;logoColor=white" alt="Tailwind CSS 4"></a>
  <a href="https://rspack.rs/"><img src="https://img.shields.io/badge/Rspack-2-FBC02D?style=flat-square&amp;logo=rspack&amp;logoColor=white" alt="Rspack 2 через Rsbuild 2"></a>
</p>

<p align="center">
  <a href="https://github.com/godzzdeal/rtool-1cd/releases/download/1.1.1-beta/rTool.1CD_1.1.1-beta_x64-setup.exe"><strong>Скачать установщик</strong></a>
  &nbsp; | &nbsp;
  <a href="https://github.com/godzzdeal/rtool-1cd/releases/download/1.1.1-beta/rtool-cli-1.1.1-beta-windows-x64.zip"><strong>Скачать CLI</strong></a>
  &nbsp; | &nbsp;
  <a href="RELEASE-NOTES.md">Описание выпуска</a>
  &nbsp; | &nbsp;
  <a href="https://github.com/godzzdeal/rtool-1cd/issues">Сообщить об ошибке</a>
</p>

---

## Возможности

- Таблицы, поля, записи и индексы.
- Поиск по данным и настройка представления полей.
- Схема связей таблиц и просмотр в HEX.
- Изменение значений, добавление и удаление записей в поддерживаемых таблицах.
- Сохранение всех правок в копию или открытую базу.

Бета-версия предназначена для файлов .1CD формата **8.3.8.0**.

## Скриншоты

<table>
  <tr>
    <td width="50%"><a href="assets/screenshots/06-records.png"><img src="assets/screenshots/06-records.png" alt="Записи таблицы" width="440"></a><br><strong>Записи таблицы</strong></td>
    <td width="50%"><a href="assets/screenshots/09-relations.png"><img src="assets/screenshots/09-relations.png" alt="Схема связей таблиц" width="440"></a><br><strong>Связи таблиц</strong></td>
  </tr>
  <tr>
    <td><a href="assets/screenshots/04-field-display.png"><img src="assets/screenshots/04-field-display.png" alt="Настройка представления полей" width="440"></a><br><strong>Представление полей</strong></td>
    <td><a href="assets/screenshots/07-editing.png"><img src="assets/screenshots/07-editing.png" alt="Редактирование записей" width="440"></a><br><strong>Редактирование записей</strong></td>
  </tr>
</table>

## CLI

**rtool-cli** — работа с базой 1С в терминале. Таблицы, поля и индексы, поиск по значениям, отбор таблиц и вкладки. Можно менять значения, добавлять и удалять записи, просматривать и отменять правки.

Сохранение доступно в новый файл или открытую базу. Запись в открытую базу требует подтверждения; резервная копия создаётся рядом с ней. Длительные операции показывают текущий этап, прогресс и время.

[Скачать CLI для Windows x64](https://github.com/godzzdeal/rtool-1cd/releases/download/1.1.1-beta/rtool-cli-1.1.1-beta-windows-x64.zip) | [SHA-256](https://github.com/godzzdeal/rtool-1cd/releases/download/1.1.1-beta/rtool-cli-1.1.1-beta-windows-x64.zip.sha256)

Распакуйте архив целиком и запустите `rtool-cli.exe`. Открыть базу: `/open "путь"`. Папка `icu` должна оставаться рядом с программой. Tauri и WebView2 для CLI не нужны.

**F1** таблицы, **F3** отбор, **Ctrl+F** поиск, **Enter / F9** изменить поле, **F10** вид полей, **F8** правки. **Ctrl+S** сохранить копию, **Ctrl+Shift+S** сохранить в базу. Команды доступны по `/help`.

<table>
  <tr>
    <td width="50%"><a href="assets/screenshots/cli-01-records.png"><img src="assets/screenshots/cli-01-records.png" alt="Записи таблицы в CLI" width="440"></a><br><strong>Таблицы и вкладки</strong></td>
    <td width="50%"><a href="assets/screenshots/cli-02-filter.png"><img src="assets/screenshots/cli-02-filter.png" alt="Отбор таблиц в CLI" width="440"></a><br><strong>Отбор таблиц</strong></td>
  </tr>
  <tr>
    <td><a href="assets/screenshots/cli-03-editor.png"><img src="assets/screenshots/cli-03-editor.png" alt="Редактирование значения в CLI" width="440"></a><br><strong>Редактирование</strong></td>
    <td><a href="assets/screenshots/cli-04-changes.png"><img src="assets/screenshots/cli-04-changes.png" alt="Список изменений в CLI" width="440"></a><br><strong>История правок</strong></td>
  </tr>
</table>

## Установка

Скачайте установщик для Windows x64 и запустите его. Приложение устанавливается для текущего пользователя.

Недостающие компоненты установщик предложит установить сам. Если потребуется ручная установка, используйте официальные страницы Microsoft:

- [Visual C++ 2010 SP1 x64](https://www.microsoft.com/en-us/download/details.aspx?id=26999) — выберите **vcredist_x64.exe**.
- [WebView2 Runtime](https://developer.microsoft.com/en-us/microsoft-edge/webview2/#download-section) — выберите **Evergreen Standalone Installer, x64**.

Установщик не подписан. [Скачать SHA-256](https://github.com/godzzdeal/rtool-1cd/releases/download/1.1.1-beta/rTool.1CD_1.1.1-beta_x64-setup.exe.sha256).

> [!IMPORTANT]
> Перед редактированием закройте базу в 1С и сделайте резервную копию. Редактируйте тестовую копию базы.

## Благодарности

Благодарю [Валерия Агеева](https://bitbucket.org/awa15/), автора [Tool_1CD](https://bitbucket.org/awa15/tool_1cd-sources), за создание инструмента и публикацию исходного кода. Его работа вдохновила меня разработать rTool 1CD на Rust.

## Обратная связь

[Создайте Issue](https://github.com/godzzdeal/rtool-1cd/issues) с версией приложения, форматом базы и шагами, которые привели к ошибке. Не прикладывайте рабочие базы и конфиденциальные данные.

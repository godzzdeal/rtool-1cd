<h1 align="center">rTool 1CD</h1>

<p align="center">Просмотр и редактирование файловых баз 1С</p>

<p align="center">
  <img src="https://img.shields.io/badge/Windows-x64-0078D4?style=flat-square" alt="Windows x64">
  <img src="https://img.shields.io/badge/версия-1.1.0--beta-2563EB?style=flat-square" alt="Версия 1.1.0-beta">
</p>

<p align="center">
  <a href="https://v2.tauri.app/"><img src="https://img.shields.io/badge/Tauri-2-FFC131?style=flat-square&amp;logo=tauri&amp;logoColor=white" alt="Tauri 2"></a>
  <a href="https://react.dev/"><img src="https://img.shields.io/badge/React-19-61DAFB?style=flat-square&amp;logo=react&amp;logoColor=white" alt="React 19"></a>
  <a href="https://www.rust-lang.org/"><img src="https://img.shields.io/badge/Rust-000000?style=flat-square&amp;logo=rust&amp;logoColor=white" alt="Rust"></a>
  <a href="https://tailwindcss.com/"><img src="https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?style=flat-square&amp;logo=tailwindcss&amp;logoColor=white" alt="Tailwind CSS 4"></a>
  <a href="https://rspack.rs/"><img src="https://img.shields.io/badge/Rspack-2-FBC02D?style=flat-square&amp;logo=rspack&amp;logoColor=white" alt="Rspack 2 через Rsbuild 2"></a>
</p>

<p align="center">
  <a href="https://github.com/godzzdeal/rtool-1cd/releases/download/1.1.0-beta/rTool.1CD_1.1.0-beta_x64-setup.exe"><strong>Скачать установщик</strong></a>
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

![Просмотр записей справочника](assets/screenshots/06-records.png)

<details>
<summary>Обзор базы</summary>

![Обзор базы](assets/screenshots/01-overview.png)

</details>

<details>
<summary>Каталог таблиц и отбор</summary>

![Каталог таблиц](assets/screenshots/02-tables.png)

![Группы таблиц](assets/screenshots/03-table-groups.png)

</details>

<details>
<summary>Представление полей и индексы</summary>

![Настройка представления полей](assets/screenshots/04-field-display.png)

![Иерархия индексов](assets/screenshots/05-indexes.png)

</details>

<details>
<summary>Редактирование записей</summary>

![Режим редактирования](assets/screenshots/07-editing.png)

![Редактор значения поля](assets/screenshots/08-cell-editor.png)

</details>

## Установка

Скачайте установщик для Windows x64 и запустите его. Приложение устанавливается для текущего пользователя.

Недостающие компоненты установщик предложит установить сам. Если потребуется ручная установка, используйте официальные страницы Microsoft:

- [Visual C++ 2010 SP1 x64](https://www.microsoft.com/en-us/download/details.aspx?id=26999) — выберите **vcredist_x64.exe**.
- [WebView2 Runtime](https://developer.microsoft.com/en-us/microsoft-edge/webview2/#download-section) — выберите **Evergreen Standalone Installer, x64**.

Установщик не подписан. [Скачать SHA-256](https://github.com/godzzdeal/rtool-1cd/releases/download/1.1.0-beta/rTool.1CD_1.1.0-beta_x64-setup.exe.sha256).

> [!IMPORTANT]
> Перед редактированием закройте базу в 1С и сделайте резервную копию. Редактируйте тестовую копию базы.

## Благодарности

Благодарю [Валерия Агеева](https://bitbucket.org/awa15/), автора [Tool_1CD](https://bitbucket.org/awa15/tool_1cd-sources), за создание инструмента и публикацию исходного кода. Его работа вдохновила меня разработать rTool 1CD на Rust.

## Обратная связь

[Создайте Issue](https://github.com/godzzdeal/rtool-1cd/issues) с версией приложения, форматом базы и шагами, которые привели к ошибке. Не прикладывайте рабочие базы и конфиденциальные данные.

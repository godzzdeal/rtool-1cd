<h1 align="center">rTool 1CD</h1>

<p align="center">Просмотр и редактирование файловых баз 1С</p>

<p align="center">
  <img src="https://img.shields.io/badge/Windows-x64-0078D4?style=flat-square" alt="Windows x64">
  <img src="https://img.shields.io/badge/версия-1.1.0--beta-2563EB?style=flat-square" alt="Версия 1.1.0-beta">
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

## Стек

- [Tauri 2](https://v2.tauri.app/) — окно приложения, системное меню и диалоги.
- [React 19](https://react.dev/) и TypeScript — интерфейс таблиц, поиска и редактирования.
- [Rust](https://www.rust-lang.org/) — чтение формата 1CD, работа с записями и индексами.
- [Tailwind CSS 4](https://tailwindcss.com/) — оформление, светлая и тёмная темы.
- [Rspack](https://rspack.rs/) через [Rsbuild 2](https://rsbuild.rs/) — сборка интерфейса.

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

<h1 align="center">Открытие .py файлов в стандартной IDLE двойным кликом</h1>
<h4 align="center">IDLE - официальная среда разработки от разработчиков Python. По умолчанию она запускается через pythonw.exe, что делает невозможным редактировать их через IDLE, открывая файлы двойным кликом. Чтобы исправить это, читайте ниже.</h4>

## В чём суть: 

- **В файлах Python в папке \Lib\idlelib есть файл idle.bat. В нём нужно заменить CurrentDir на прямые пути к pythonw.exe и idle.pyw (1 - в папке Lib, 2 - в Lib\idlelib).**

Для конвертации **.bat в .exe** можно использовать программу от **[Tokyoneon](https://github.com/tokyoneon/B2E)**, а иконку взять из Python39\Lib\idlelib\Icons. В папке Python39\Lib\idlelib\ есть **idle.bat** от **разработчиков Python**, но чтобы при конвертации полученный .exe заработал, необходимо указать прямой путь к **pythonw.exe и idle.pyw**.

## Использование:
- После создания **.exe файла** сохраните его в удобном месте или через меню **"Открыть с помощью"** выберите его.

## Обратная связь:
- Telegram: https://t.me/MatroCholo

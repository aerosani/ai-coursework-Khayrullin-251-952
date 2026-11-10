[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aerosani/ai-coursework-Khayrullin-251-952/blob/main/lab1/notebooks/lab1.ipynb)

# Практическое занятие 1. Рабочее окружение

Автор: Хайруллин Тахир Зиннурович, группа 251-952

## Структура папки lab1

Папка data содержит данные, папка notebooks – ноутбук lab1.ipynb, файл requirements.txt – список библиотек.

## Запуск на локальном компьютере

В папке lab1:

1. Создать окружение: python -m venv .venv
2. Включить окружение: .venv\Scripts\activate (macOS и Linux: source .venv/bin/activate)
3. Установить библиотеки: pip install -r requirements.txt
4. Открыть notebooks/lab1.ipynb в VS Code и выбрать ядро .venv

## Сравнение VS Code и Colab

| | VS Code | Colab |
|---|---|---|
| Версия Python | 3.11.16 | 3.13.18 |
| Версия pandas | 3.1.1 | 2.2.3 |
| Где хранятся файлы | c:\Users\user\work\lab1 | на временном сервере Google, файлы удаляются при отключении |
| Что потребовалось для запуска | установленные Python, VS Code, Git, расширения Python и Jupyter | браузер, аккаунт Google, ссылка на ноутбук на GitHub |

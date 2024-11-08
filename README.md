# Лазимов Даниил Ибрагимович М3103
# labwork3_466461 README 

# Расширение для генерации документации в VSCode

Это расширение для Visual Studio Code предоставляет простой интерфейс для генерации документации с использованием Doxygen. Расширение позволяет пользователям указывать путь к директории или использовать директорию рабочего пространства по умолчанию для генерации документации.

## Возможности

- Пользовательский интерфейс: Показывает форму для ввода нужного пути директории для генерации документации.
- Директория по умолчанию: Позволяет автоматически заполнить текущую директорию рабочего пространства.
- Генерация документации: Выполняет Doxygen для генерации документации в указанной директории.

## Установка

1. Клонируйте этот репозиторий в ваш .vscode/extensions каталог.
2. Откройте клонированный каталог в Visual Studio Code.
3. Запустите расширение, нажав F5.

## Использование

1. Расширение можно активировать с помощью сочетания клавиш Ctrl+F1.
2. Откроется форма в webview:
   - Введите путь к директории, где вы хотите сгенерировать документацию.
   - Нажмите "Директория по умолчанию", чтобы автоматически заполнить текущую директорию рабочего пространства.
3. Нажмите кнопку "Отправить", чтобы начать генерацию документации.

## Как это работает

- Webview: Расширение показывает webview форму с полями для ввода пути к директории.
- VSCode API: Обеспечивает коммуникацию с webview для передачи пути директории и команд.
- Выполнение Doxygen: Использует функцию child_process.exec, чтобы запустить команды Doxygen в указанной директории.

## Команды

- docgenerator.generate: Открывает форму в webview для ввода нужного пути для генерации документации.

## Разработка

Если вы хотите изменить или улучшить расширение:

1. Откройте проект расширения в Visual Studio Code.
2. Обновите исходники по мере необходимости.
3. Проверьте изменения, используя F5, чтобы запустить расширение в новом окне для разработки расширений.

## Устранение неполадок

- Сообщения об ошибках: Проверьте консоль вывода VSCode и терминал на предмет логов ошибок, если расширение не работает должным образом.



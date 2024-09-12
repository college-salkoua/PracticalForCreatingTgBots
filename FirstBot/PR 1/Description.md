# Знайомтсво з бібліотекою [Aiogram](https://docs.aiogram.dev/uk-ua/dev-3.x/) 
aiogram — це сучасна та повністю асинхронна структура для API Telegram Bot, 
написана на Python 3.8+ з використанням asyncio та aiohttp.

Зробіть своїх ботів швидкими та потужнішими!

# Інсталяція
### Завантаження poetry (віртуальне середовище для проєкту)
```powershell
(Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | py -
```
### Завантаження бібліотеки aiogram
+ ### Ініціалізація проєкту (віртуального середовища) (пройдіть всі пункти)
    ```bash
    poetry init
    ```
+ ### Додаємо aiogram в VENV (Віртуальне середовище)
    ```bash
    poetry add aiogram
    ```

# Структура проєкту
### Ми будемо використовувати [src](https://packaging.python.org/en/latest/discussions/src-layout-vs-flat-layout/) структуру 
```tree
.
├── README.md
├── pyproject.toml (VENV)
├── src/
│    └── awesome_package/
│       ├── __init__.py
│       ├── __main__.py
│       └── module.py
└── tools/
    ├── generate_awesomeness.py
    └── decrease_world_suck.py
```




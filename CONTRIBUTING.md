Contributing
Как начать
1. Клонируй репозиторий.
2. Установи инструменты: pip install pre-commit black isort flake8 flake8-bugbear Flake8-pyproject
3. Включи pre-commit install

Как вносить изменения
1. Создайте ветку: git checkout -b feature/название
2. Внесите изменения и сделайте коммит. Линтеры запустятся сами.
3. Если хук что-то исправил, сделайте git add и коммит ещё раз.
4. Отправьте ветку и откройте Pull Request в main.

Линтеры
- black форматирует код
- isort сортирует импорты
- flake8 ищет ошибки
- pre-commit run --all-files запускает всё сразу

Настройки лежат в pyproject.toml.

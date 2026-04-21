# AS KODA x RAIN Integration Project

Проект для проработки требований, подготовки прототипа и консолидации исходных материалов по интеграции АС КОДА и AI-агента RAIN.

## Структура проекта

- `docs/requirements/` — рабочие требования и решения по ним.
- `prototype/` — прототипы и материалы по проверке пользовательских сценариев.
- `materials/source/` — каталог исходных материалов от заказчика и команды.
- `project/` — план работ, этапы и договоренности по проекту.
- `.github/` — шаблоны и инструкции для работы в GitHub.

## Базовый сценарий работы

1. Согласовать требования в `docs/requirements/`.
2. Подготовить и уточнить прототип в `prototype/`.
3. Поддерживать актуальность источников в `materials/source/`.
4. Фиксировать этапы выполнения в `project/`.

## Как оформить как отдельный проект в GitHub

1. Инициализировать репозиторий локально:
   - `git init`
   - `git add .`
   - `git commit -m "Initialize AS KODA x RAIN integration project structure"`
2. Создать новый репозиторий в GitHub (через UI или CLI `gh repo create`).
3. Привязать remote и отправить ветку:
   - `git remote add origin <repo-url>`
   - `git branch -M main`
   - `git push -u origin main`

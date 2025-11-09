# HelloCompose

**HelloCompose** — навчальний Android-додаток на Jetpack Compose.  
Розроблено у рамках лабораторної роботи для ознайомлення з сучасними підходами до розробки мобільних застосунків, організацією проекту через Git/GitHub Flow та використанням CI.

## Про проект

- Використано шаблон Empty Compose Activity
- Додаток реалізовано на основі Jetpack Compose (Material 3)
- Мінімальна версія Android — API 26

## Основний функціонал

- Демонстрація базового екрану з текстом і кнопкою
- Взаємодія зі станом через Compose
- Приклад компонування UI через Material

## Структура репозиторію

- `app/src/main/java/com/example/hellocompose/` — вихідний код застосунку
- `app/src/main/java/com/example/hellocompose/ui/theme/` — файли кольорових схем та типографіки
- `.github/ISSUE_TEMPLATE/` — шаблони задач (issue)
- `.github/workflows/` — сценарії GitHub Actions для CI

## Git-Flow

- Гілка **main** — продакшн (релізи)
- Гілка **develop** — основна для розробки
- Для нових фіч використовуйте команди git-flow:  
  `git flow feature start назва-фічі`

## CI/CD

- В проекті налаштовано автоматичну збірку та тести через GitHub Actions
- При кожному push або pull request виконується збірка та запуск unit-тестів

## Швидкий старт

![Android CI](https://github.com/d3cryptex/HelloCompose/actions/workflows/android-
ci.yml/badge.svg)

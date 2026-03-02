# Автоматизированные тесты для UI Course

## **[English](../README.md)** | **Русский**

Этот проект реализует автоматизированные тесты для
[UI Course Test Application](https://nikita-filonov.github.io/qa-automation-engineer-ui-course/#/auth/login).
Тесты написаны с использованием **Python**, **Pytest**, **Allure** и **Playwright**. Исходный код тестового приложения доступен
на [GitHub](https://github.com/Nikita-Filonov/qa-automation-engineer-ui-course).

[![UI tests](https://github.com/lobanov-qa/autotests-ui/actions/workflows/tests.yml/badge.svg)](https://github.com/lobanov-qa/autotests-ui/actions/workflows/tests.yml) ![Python](https://img.shields.io/badge/python-3670A0?style=flat-square&logo=python&logoColor=ffdd54) ![Playwright](https://img.shields.io/badge/-playwright-%232EAD33?style=flat-square&logo=playwright&logoColor=white) ![Pytest](https://img.shields.io/badge/pytest-%23ffffff.svg?style=flat-square&logo=pytest&logoColor=2f9fe3) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat-square&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=flat-square&logo=githubactions&logoColor=white) 

## Обзор проекта

Цель этого проекта — автоматизация тестирования приложения UI Course. Автоматизированные тесты проверяют различные
функциональности приложения, чтобы гарантировать его стабильность и корректность. Структура проекта следует лучшим практикам
организации тестового кода с понятными, поддерживаемыми сценариями.

## Начало работы
> ⚠️ **Важно:** проект тестирует учебную  платформу [UI Course Test Application](https://nikita-filonov.github.io/qa-automation-engineer-ui-course/#/auth/login) которая должна быть запущенна локально
 
### Клонирование репозитория

Для начала работы клонируйте репозиторий проекта с помощью Git:

```bash
git clone https://github.com/lobanov-qa/autotests-ui.git
cd autotests-ui
```

### Создание виртуального окружения

Рекомендуется использовать виртуальное окружение для управления зависимостями проекта. Следуйте инструкциям для вашей операционной
системы:

#### Linux / MacOS

```bash
python3 -m venv venv
source venv/bin/activate
```

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Установка зависимостей

После активации виртуального окружения установите зависимости проекта, перечисленные в `requirements.txt`:

```bash
pip install -r requirements.txt
```

### Дополнительная настройка Playwright (если необходимо)

Если вы впервые запускаете Playwright, может потребоваться установка необходимых браузеров:

```bash
playwright install
```

### Запуск тестов с генерацией Allure-отчета

Для запуска тестов и генерации Allure-отчета используйте следующую команду:

```bash
pytest -m "regression" --alluredir=./allure-results
```

Это выполнит все тесты в проекте и отобразит результаты в терминале.

### Просмотр Allure-отчета

После выполнения тестов вы можете сгенерировать и просмотреть Allure-отчет с помощью:

```bash
allure serve allure-results
```

Эта команда откроет Allure-отчет в вашем браузере по умолчанию.

---

## 📞 Контакты

Ищу возможность начать карьеру в автоматизации тестирования. Готов к тестовому заданию, код-ревью и собеседованиям.

- **GitHub:** [lobanov-qa](https://github.com/lobanov-qa)
- **LinkedIn:** [evgenii-lobanov-qa](https://www.linkedin.com/in/evgenii-lobanov-qa/)
- **Telegram:** [lobanov_e_i](https://t.me/lobanov_e_i)


---


*Проект создан в рамках курса [«Автоматизация тестирования UI с Python и Playwright»](https://stepik.org/course/234842/info) (автор — Никита Филонов).*  
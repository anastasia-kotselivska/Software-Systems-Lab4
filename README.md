
SOFTWARE-SYSTEMS-LAB5

[![Python CI Application](https://github.com/anastasia-kotselivska/Software-Systems-Lab4/actions/workflows/python-app.yml/badge.svg)](https://github.com/anastasia-kotselivska/Software-Systems-Lab4/actions/workflows/python-app.yml)

Проєкт демонструє налаштування процесів безперервної інтеграції (CI) та автоматичного контролю якості коду.

* **Математичний модуль:** операції додавання та віднімання.
* **Автоматичне тестування:** перевірка логіки через `unittest`.
* **Статичний аналіз коду:** перевірка стандартів PEP8 лінтером `flake8`.
* **Захист коду:** використання GitHub Secrets та захист гілки `main`.

## Запуск тестів локально
```bash
python -m unittest test_calculator.py
```

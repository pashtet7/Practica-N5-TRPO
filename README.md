# Сумма чисел в массиве

## Описание
Программа принимает массив чисел, введенный пользователем, и вычисляет их сумму.

## Используемые технологии
- Язык программирования: Python  
- Требуемая версия: Python 3.x

## Используемые библиотеки
Программа использует только стандартную библиотеку Python, поэтому не требует установки дополнительных пакетов.

## Структура проекта
- `sum_array_program.py` – основной файл программы, содержащий функции для работы с массивом чисел.
- `diagram.png` – диаграмма алгоритма работы программы.
- `README.md` – документация проекта.

## Количество и назначение компонентов
- **Файл кода (`sum_array_program.py`)**:
  - **Функция `sum_array(numbers)`** – принимает список чисел и возвращает их сумму.
  - **Функция `main()`** – обрабатывает ввод пользователя, преобразует данные и вызывает `sum_array()`.

## Входные параметры
- **Ввод:**
  - Пользователь вводит строку чисел, разделенных пробелами (например, `1 2 3 4 5`).
  - Данные преобразуются в список целых чисел (`list[int]`).
- **Выход:**
  - Выводится сумма всех чисел в списке.

## Как запустить
1. Склонируйте репозиторий:
   ```bash
   git clone <ссылка на репозиторий>
   ```
2. Перейдите в папку проекта:
   ```bash
   cd sum-array-project
   ```
3. Запустите скрипт:
   ```bash
   python sum_array_program.py
   ```


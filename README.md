# Лабораторная работа 1
**Назначение программы:** расчет и построение графика погашения ипотечного кредита.

## Требования:
1. Начальные параметры задачи считываются из Excel-файла.
2. Подсчет графика погашения ипотечного кредита:
    + дифференцированными платежами;
    + аннуитетными платежами.
3. Формирование результатов расчетов в таблице.
4. Интерфейс должен содержать:
    + выбор файла;
    + выбор способа погашения кредита;
    + просмотр графика погашения кредита;
    + вывод таблицы (в интерфейсе и/или в Excel).
5. Использовать принципы ООП.

## Результаты:

Для того, чтобы запустить приложение и рассчитать график платежей, необходимо запустить класс Main. <br> (Путь: src/main/java/main/Main.java)

### Функционал:
1. Программа считывает данные о кредите из таблицы.
2. Программа рассчитывает график платежей.
3. Программа выводит график платежей в таблице во всплывающем окне.
3. Программа сохраняет график платежей в таблице.

Пример корректной таблицы с входными данными: main/examples/example_in.xlsx
<br> ![Корректная таблица](https://github.com/alenatorgasheva/JavaMastersProjects/blob/develop/src/main/java/main/examples/correct-table.jpg)

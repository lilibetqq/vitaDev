# Тестовое задание web-разработчика
Создать калькулятор способный выполнять основные арифметические действия(сложение, вычитание, умножение, деление). Рекомендовано писать на числом js(ES6) Допускается использование js фреймворка vue.js, препроцессоров SCSS, SASS и сборщиков webpack, gulp.
### Основные требования к выполнению:
  - Верстка и цветовая палитра должны соответствовать макетам, представленным в папке с исходниками
  - Калькулятор должен уметь обрабатывать как целые, так и десятичные числа, обрабатывать исключения(число + строка, умножение на ноль и т.д.).
  - Арифметические операции должны обрабатываться на стороне бэка.
  - Результаты операций средствами php должны складываться в отдельный файл. Пример:
 ```
1. 2+3=5
2. 7+3=10
3. 2-3=-1
...
n. 13*2=26
```
  - Исключения должны складываются в отдельный лог файл, как в примере выше.

### Необязательные, но желательные к выполнению
  - Умение работать с последовательностью типа: `10+12-2+2*3`, учитывая последовательность выполнения арифмитических действий
  - Реализация с использованием SCSS, SASS в рамках выполнения тестового задания.
  - Добавить функционал ввода данных с клавиатуры  


### Пример использования

1. Пользователь вводит 2 числа над которыми будет производиться арифметическая операция: 2+2 после чего нажимает на знак: =
2. Формируется POST запрос на бэк, где производится расчет и возврат результата.
3. Результат отображается пользователю.

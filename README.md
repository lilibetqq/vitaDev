# Тестовое задание web-разработчика
Создать калькулятор способный выполнять основные арифметические действия(сложение, вычитание, умножение, деление). Не рекомендуется использовать зависимости, такие как jquery, bootstrap, skeleton и п. Допускается использование js фреймворка vue.js, препроцессоров SCSS, SASS и сборщиков webpack, gulp
### Основные требования к выполнению:
  - Верстка и цветовая палитра должны соответствовать макетам представленным в папке с исходниками
  - Калькуляор должен уметь обрабатывать как целые, так и десятичные числа, обрабатывать исключения(число + строка, умножение на ноль и т.д.).
  - Результаты операций в режиме реального времени должны передаваться на бэк, средствами php складываться в отдельный файл. Пример:
 ```
1. 2+3=5
2. 7+3=10
3. 2-3=-1
...
n. 13*2=26
```
  - Исключения должны складываються в отдельный лог файл, как в примере выше.
  - Калькулятор должен уметь работать как полноценный калькулятор
### Необязательные, но желательные к выполнению
  - Умение работать с последовательностью типа: `10+12-2+2*3`, учитывая последовательность выполнения арифмитических действий
  - Реализация с использованием SCSS, SASS в рамках выполнения тестового задания.

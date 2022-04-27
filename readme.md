# Модуль 20

---

#### Первоначальный проект находится по https://disk.yandex.ru/d/72Cr-D7Mc2a7Bg

> github pages - https://poppiehub.github.io/module20_homework/

### Цель задания: 
- Проверить семантику, валидность верстки и оптимизировать верстку по принципам: **DRY, KISS, YAGNI, БЭМ, SOLID**.

Через таск-менеджер **Gulp** подключены препроцессоры **Pug** и **Sass**.


### Исправлено по принципам:
- **DRY** (Don't Repeat Yourself):
    - Использования циклов в Pug создает одинаковые блоки;
    - Использование методологии БЭМ при написании стилей, отдельные классы с общими стилями для повторяющихся элементов.

- **KISS** (Keep It Simple, Student):
    - Синтаксис Pug без угловых скобок и закрывающих тегов очень упрощает написание и чтение;
    - Переменные для цвета и шрифтов в Scss упрощают внесение изменений в стили;

- **YAGNI** (You Ain't Gonna Need It):
    - Была изменена верстка в некоторых местах с удалением лишних блоков;
    - Были установленны дополнения для Gulp, проверяющие, упрощающие и сжимающие html и css файлы;

- **БЭМ** (Блок-Элемент-Модификатор): Методология БЭМ также включает в себя многое из принципов **SOLID** (single responsibility, open–closed, Liskov substitution, interface segregation и dependency inversion).

### Были подключены следующие плагины **Gulp**:

- gulp-pug - конвертирует pug в html
- gulp-pug-linter - линтер для pug
- gulp-sass - конвертирует scss/sass в css
- gulp-autoprefixer - расставляет необходимые префиксы в css
- gulp-shorthand - сокращает запись css-свойств
- gulp-csslint - линтер для css
- gulp-clean-css - сжимает css



LICENSE: [MIT](./license.md)

---

AUTHOR: PoppieHub@GitHub

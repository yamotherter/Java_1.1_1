# # Отчёт о тестировании *Credit Card Number Validator*

## Краткое описание

25.07.2021 - 25.07.2021 было проведено тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час.

В результате тестирования выявлены следующие дефекты:
* [Карты American Express не проходят валидацию в программе IntelliJ IDEA · Issue #1 · yamotherter/Java_1.1_1 · GitHub](https://github.com/yamotherter/Java_1.1_1/issues/1#issue-954316293)

## Описание процесса тестирования

В качестве тестовых данных использовались данные сайта Get Credit Card Numbers:
* Visa 4485800874652455; 4716900169274105; 4532945315306188 — Result is OK
* Mastercard 5118984530210353; 5199164547074116; 5208781698621749 — Result is OK
* Discover 6011683594567155; 6011250040573516;   
6011504905141789 — Result is OK
* American Express 377791788511482 — Result is FAIL
* American Express 376687107656134 — Result is FAIL
* American Express 372968188260408 — Result is FAIL

Тестирование производилось в следующем окружении:
* MacOs Big Sur 11.04
* Openjdk version "11.0.11"


# Отчет о тестировании <Credit Card Number Validator>

## Краткое описание

04.03.21 - 04.03.21 было проведено компонентное тестирование приложения Credit Card Number Validator

На тестирование затрачено: 0,5 часа

В результате тестирования выявлен следующий дефект:
  * [При введении в Validator номера карты American Express получаем результат FAIL при прохождении теста](https://github.com/Amoralez84/Java1.2/issues/1)

## Описание процесса тестирования

### В процессе тестирования использовались следующие артефакты:
* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* [Credit Card Number Generator & Validator](https://www.freeformatter.com/credit-card-number-generator-validator.html)
### В качестве тестовых данных использовались данные [Credit Card Number Generator & Validator](https://www.freeformatter.com/credit-card-number-generator-validator.html):
* При вводе номера карты VISA - сообщение "OK" при запуске программы
* При вводе номера карты VISA Electron - сообщение "OK" при запуске программы
* При вводе номера карты Maestro - сообщение "OK" при запуске программы
* При вводе номера карты MasterCard - сообщение "OK" при запуске программы
* При вводе номера карты American Express - сообщение "FAIL" при запуске программы

![Баг 1 2 Java](https://user-images.githubusercontent.com/79215308/122687406-fbc86c00-d21e-11eb-862c-ce4502d77c92.png)

 ![Main – Main java 2021-06-25 16 09 49](https://user-images.githubusercontent.com/79215308/123430372-c5993c80-d5d0-11eb-8d3d-70a4d6896552.png)

 ![Main – Main java 2021-06-25 16 08 21](https://user-images.githubusercontent.com/79215308/123430381-c92cc380-d5d0-11eb-963a-464e07f7fb8d.png)

Тестирование проводилось в следующем окружении:
* Windows10 X64
* Openjdk 11.0.10



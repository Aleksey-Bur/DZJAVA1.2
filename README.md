# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

15.01.2021 - 15.01.2021 было проведено ручное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 2 часа.

В результате тестирования выявлены следующие дефекты:
 * [Приложение пропускает невалидные данные карты](https://github.com/Aleksey-Bur/DZJAVA1.2/issues/1)

## Описание процесса тестирования

План тестирования:

1. Открыть Credit Card Number Validator в IntelliJ IDEA.

2. Внести тестовые данные в строку String number = "";

Необходимо проверить, что:

1. Функциональность валидации номера банковской карты работает.
2. Валидные данные проходят проверку : Result is ОК
3. Невалидные данные не проходят проверку : Result is FAIL

В качестве тестовых данных использовались данные, взятые с ресурса [Credit Card Number Generator & Validator](https://www.freeformatter.com/credit-card-number-generator-validator.html)

Валидные номера:

* VISA 4716795981557418

* Visa Electron 4026934642273470

* MasterCard 2720994600189434

* Maestro 6762013591873284


Невалидные номера:

* American Express 372866864591320

* Discover  6011295341965137667

* Visa 4000000000000002

Тестирование производилось в следующем окружении:

* Windows 10 Pro, x64

* java: openjdk version "11.0.9.1" 2020-11-04
  OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9.1+1)
  OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.9.1+1, mixed mode)

* IntelliJ IDEA Community Edition 2020.3.1 x64
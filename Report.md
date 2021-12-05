#Отчет о тестировании "Credit Card Number Validator"

##Краткое описание

05.12.2021 было проведено исследовательское тестирование приложения "MoneyTransfer" методом черного ящика.

На тестирование было потрачено 2 часа.

В результате тестирования был выявлен следующий дефект: номера некоторых брендов пластиковых карт не принимаются, приложение выдает ошибку.

##Описание процесса тестирования

**В процессе тестирования были использованы следуюище артефакты:**
1. Приложение "Credit Card Number Validator"
2. Среда разработки IntelleJ IDEA
3. Credit Card Number Generator
4. Система контроля версий Git


**В качестве тестовых данных использовались данные https://freeformatter.com/credit-card-number-generator-validator.html:**
* VISA: 4716481078870788
* MasterCard: 5482503536816530
* Discover: 6011919112393611
* American Express (AMEX): 344963569075736
* JCB: 3536286718967203
* Diners Club - North America: 5401811995490673
* Diners Club - Carte Blanche: 30519463726664
* Diners Club - International: 36376893058778
* Maestro: 5020969136887941 - принимает
* Visa Electron: 4913098379832456
* InstaPayment: 6398097283066994

Все номера карт валидные и должны приниматься приложением

**Тестирование производилось в следующем окружении:**
* Windows 10 Pro 64 разряда
* Java 11 Amazon Corette
* IntelliJ IDEA 2021.3 (Community Edition)
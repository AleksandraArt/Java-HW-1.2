# Отчёт о тестировании приложения "Credit Card Number Validator"
## Краткое описание
20.11.2020 было проведено функциональное тестирование приложения Credit Card Number Validator. 
Было проведено 44 теста для проверки корректной работы функции.
На тестирование было потрачено 2 часа.

В результате тестирования выявлены следующие дефекты: 
 * Валидные номера карт длиною в 15 символов не проходят проверку [репорт_номера_карт_15_символов](https://github.com/AleksandraArt/21.11/issues/3);
 * Валидные номера карт длиною в 18 символов не проходят проверку [репорт_номера_карт_18_символов](https://github.com/AleksandraArt/21.11/issues/2);
 * Валидные номера карт длиною в 14 символов не проходят проверку [репорт_номера_карт_14_символов](https://github.com/AleksandraArt/21.11/issues/1). 

## Описание тестов
Было проведено позитивное функциональное тестирование функции.
Тестирование осуществлялось на Java 11.

## Результаты
В ходе тестирования выведено 80% успешных и 20% не успешны тестов.

## Общие рекомендации
Следует произвести доработку функции приложения принятия валидных номеров карт.
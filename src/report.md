
##Отчёт о тестировании Credit Card Number Validator

27/07/20 - 27/07/20
Было проведено тестирование приложения  Credit Card Number Validator
 
На тестирование затрачено: один час.

В результате тестирования выявлены следующие дефекты:
<https://github.com/Irina-Bebenina/DZ-Java1.2/issues/1>

В процессе тестирования использовалось руководство по установке IntelliJ IDEA.

В качестве тестовых данных использовались Единые стандарты банковских карт ISO/IEC 7810:
1. Ввод валидных данных номера карты 535171942781074.Ожидаемый результат :Result is - Оk. 
2. Ввод валидных данных номера карты 6785678456749876. Ожидаемый результат :Result is - Оk.
3. Ввод невалидных данных 0000000000000000 - Ожидаемый результат :Result is - FAIL

**Тестирование производилось в следующем окружении:

версия windows 10.0.18363.959
версия Java "11.0.8"**

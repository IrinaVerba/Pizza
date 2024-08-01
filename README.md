# Pizza

# **Оформление заказа**

1. Система автоматически заполняет поля (со страницы «Персональная информация»):
-Имя,фамилия 
-Контактный номер телефона 
-Адрес доставки

2. Пользователь может отредактировать Адрес доставки или указать Самовывоз из
пиццерии

3. Система предлагает выбор времени доставки (диапазон 30 минут)

4. Пользователь выбирает удобное время доставки

5. Система предлагает ввод промокода

 1 Пользователь вводит промокод
 2 При корректном промокоде Система пересчитывает сумму заказа
 3 При неправильном промокоде Система выдает ошибку «Промокод не верный»

7. Система предлагает способы оплаты

*Основной сценарий*

6.1 Пользователь выбирает из вариантов:

6.1.1 Онлайн оплата
-Система предлагает ввести данные карты пользователя (номер карты, срок
действия, СVV)
-Пользователь вводит данные карты
-Пользователь нажимает кнопку
-При корректной оплате Система выдает информацию «Заказ успешно оформлен»
-При возникновении ошибки Система выдает информацию «Пожалуйста, проверьте
корректность введенных данных»
-При отсутствии нужной суммы на карте Система выдает ошибку «Недостаточно
средств для оплаты»

*Альтернативный сценарий*

6.1.2 Наличными курьеру
-Система запрашивает с какой суммы необходима сдача
-Пользователь вводит сумму
-Пользователь нажимает кнопку
-Система выдает информацию «Заказ успешно оформлен»
-При возникновении ошибки Система выдает информацию «Пожалуйста, проверьте
корректность введенных данных»

6.1.3 Картой курьеру
-Пользователь нажимает кнопку
-Система выдает информацию «Заказ успешно оформлен»

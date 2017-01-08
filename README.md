# WooCommerce DaData
Быстрый ввод адресов, ФИО и e-mail при оформлении заказа.

![Demo](https://github.com/troyanov/woocommerce-dadata/raw/master/demo.gif)

# Описание
Данный плагин добавляет функцию автодополнения к следующим полям при оформлении заказа:

* Имя
* Фамилия
* Email
* Адрес

После выбора предложенного варианта для поля Адрес, автоматически заполняются поля:

* Населённый пункт
* Область/регион
* Почтовый индекс

Использование данного плагина значительно сокращает время ввода информации, а также снижает количество ошибок при указании адреса.

**Важно!**
Данный функционал работает только для адресов Российской Федерации. 


# Установка
Следуйте общим инструкциям установки плагинов для WordPress. После активации необходимо настроить плагин (вкладка **Настройки DaData** в меню настроек WooCommerce).
Для получения API-ключа необходимо зарегистрироваться в [DaData](https://dadata.ru/api/suggest/).

# Совместимость
* WordPress = 4.7
* WooCommerce = 2.6.11
* Storefront* = 2.1.6

**Плагин разрабатывался под конкретную задачу, для бесплатной темы WooCommerce Storefront и не тестировался с другими темами.*

# WooCommerce DaData
Быстрый ввод адресов, ФИО и e-mail при оформлении заказа. 

![Demo](https://github.com/troyanov/woocommerce-dadata/raw/master/demo.gif)

# Описание
Использование данного плагина значительно сокращает время ввода информации, а также снижает количество ошибок. Плагин добавляет функцию автодополнения к следующим полям при оформлении заказа:

* Имя
* Фамилия
* Email
* Адрес

После выбора предложенного варианта для поля Адрес, автоматически заполняются поля:

* Населённый пункт
* Область/регион
* Почтовый индекс

**Важно!**
Данный функционал работает только для адресов Российской Федерации. 

# Дополнительные подсказки
## Название компании
Поиск осуществляется путем ввода любых из перечисленных данных в поле с названием `billing_company`:
* Название компании (либо ФИО для ИП)
* Адрес компании
* ИНН
* КПП
* ОГРН

После выбора организации из подсказки, следующие поля формы будут автоматически заполнены:
* `billing_company`
* `billing_address`
* `billing_inn`
* `billing_kpp`
* `billing_ogrn`

## Наименование банка
Поиск осуществляется путем ввода любых из перечисленных данных в поле с идентификатором `billing_bank`:
* Наименование банка
* Адрес
* БИК
* SWIFT
* Корреспондентский счет в ЦБ РФ

После выбора банка из подсказки, следующие поля формы будут автоматически заполнены:

* `billing_bank`
* `billing_bank_address`
* `billing_bank_bic`
* `billing_bank_swift`
* `billing_bank_correspondent_account`


# Установка
Следуйте общим инструкциям установки плагинов для WordPress. После активации необходимо настроить плагин (вкладка **DaData** в меню настроек WooCommerce).
Для получения API-ключа необходимо зарегистрироваться в [DaData](https://dadata.ru/api/suggest/).

# Совместимость
* WordPress = 4.7
* WooCommerce = 2.6.11
* Storefront* = 2.1.6

**Плагин разрабатывался под конкретную задачу, для бесплатной темы WooCommerce Storefront и не тестировался с другими темами.*

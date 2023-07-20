|Название вопроса|Полученный ответ|
|-|-|
|Какой запрос(-ы) отправляется на сервер для получения списка типов товаров в шторке "Каталог"| POST https://sbermegamarket.ru/api/mobile/v1/catalogService/catalog/menu|
|Какой запрос(-ы) отправляется на сервер при использовании поиска товаров в каталоге?|POST https://sbermegamarket.ru/api/mobile/v3/catalogService/catalog/searchSuggest
||POST https://sbermegamarket.ru/api/mobile/v1/catalogService/catalog/search|
||POST https://sbermegamarket.ru/api/mobile/v2/cartService/filters/search|
|Какой запрос(-ы) отправляется на сервер при поиске региона или города в модалке выбора вашего региона?|POST https://sbermegamarket.ru/api/mobile/v1/addressSuggestServise/address/suggest|
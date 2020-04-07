# CROSSBOT
### Automatic Trading Bot based on crossing of EMA indicators

## Installation:

To run the code, you need a server with a configured php and with extension of **curl_php**

If your server is installed on the local machine and has the address:
```
http://127.0.0.1/
```
then extract the contents to the root folder:
```
products/crossbot/index.html
js/aex.js 
js/cookies.html 
js/xhr.js
api/binance_api.php
api/bitfinex_api.php
api/huobi_api.php
api/poloniex_api.php
```
For launch bot type in adress bar `http://127.0.0.1/products/crossbot`

The bot sends buy orders when fast EMA cross up slow EMA.

The bot sends sell orders at when fast EMA cross down slow EMA.

# [RU] CROSSBOT

## Установка:

Для работы кода, вам необходим сервер с настроенным php и в частности обязательным расширением **curl_php**

Если ваш сервер установлен на локальной машине и имеет адрес:
```
http://127.0.0.1/
```
то распакуйте содержимое в корневую папку:
```
products/crossbot/index.html
js/aex.js 
js/cookies.html 
js/xhr.js
api/binance_api.php
api/bitfinex_api.php
api/huobi_api.php
api/poloniex_api.php
```
Для запуска бота набирайте в адресной строке `http://127.0.0.1/products/crossbot`

Бот отсылает ордера на покупку, когда быстрая скользящая пересекает вверх медленную скользящую.

Бот отсылает ордера на продажу, когда быстрая скользящая пересекает вниз медленную скользящую.

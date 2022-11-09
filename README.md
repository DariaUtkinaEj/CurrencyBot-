## Currency Telegram Bot 

This bot is able to show the currency at the moment by the currency code (ISO4217 standard). 

#### In the project I used the following tools:

1) axios library to make requests to a third-party service (connect to a third-party api: in my case, axios helps to request the exchange rate from the monobank website.
[axios](https://github.com/axios/axios)

2) monobank api is free ukrain service, this api has public methods. To access it, you do not need to receive any keys or tokens. 
[monobank api](https://api.monobank.ua/bank/currency)

3) telegraf framework
[telegraf](https://github.com/telegraf/telegraf)

4) currency codes - ISO4217 standart (run 'npm install currency-codes --save')

5) Telegram Bot API

6) Nodemon (run 'npm install -g nodemon')

7) NodeJS v 19.0.0

8) npm v 8.19.2
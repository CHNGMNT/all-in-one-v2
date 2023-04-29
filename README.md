[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&lines=All-in-one+V2)](https://git.io/typing-svg)

Идеальный скрипт-V2 для ведения фермы. Освоив его, ты сможешь (идет перечисление модулей) :
1. Очень быстро смотреть баланс любой монеты в evm сети через web3.
2. Смотреть баланс всех монет, протоколов и нфт через debank.
3. Выводить монеты с этих бирж : binance, mexc, kucoin, bybit, huobi.
4. Выводить монеты с okx : добавлена функция вывода с суб-аккаунтов.
5. Выводить любые монеты в любой сети с evm кошельков (метамаск).
6. Делать свапы на 1inch во всех сетях, которые там доступны (включая zksync).
7. Делать бридж нативного токена в evm сетях через orbiter (включая zksync).
8. Делать бриджи и свапы на [woofi](https://fi.woo.org/) (бриджи через layerzero кстати)

# Настройка.

1. Вся настройка модулей и апи ключей делается в файле `setting.py`, их настройка описана в этом же файле. 
2.  В папке data есть 3 файла : `wallets.txt`, `recipients.txt`, `proxies.txt` :
- `wallets.txt` - сюда записываем кошельки (приватники / адреса).
- `recipients.txt` - сюда записываем адреса для трансфера, используется только в модуле transfer когда выводим с кошелька на адрес. 1 кошелек = 1 адрес.
- `proxies.txt` - сюда записываем прокси, они используются только в debank чекере, без них он работать не будет. Чем больше, тем лучше.
3. Настраивать модули нужно в функциях value в файле `setting.py`.
4. Запускать нужно файл `MAIN.py`

Устанавливаем библиотеки : `pip3 install -r requirements.txt`

! Огромная просьба сначала все прочитать на 10 раз, все протестировать, погуглить и только потом задавать вопросы в наш код чат. В личку админу с вопросами по коду просьба не писать, он не ответит.

Паблик : https://t.me/hodlmodeth. [ code ] чат : https://t.me/code_hodlmodeth.

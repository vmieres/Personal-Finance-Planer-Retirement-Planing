# **Financial-Planning**
![](https://keilfp.com/wp-content/uploads/2022/10/5-step-retirement-plan-videos.jpg)

#  **Tool for a personal financial planner and retirement planning**

 This repo is about creating a tool that helps people's assess their financial health. 
 
 Using the ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAB6klEQVR4AbVWMUjDQBS9feo+ddTEIaM7dB/cofvQHdzRzS7imOg+uEN3cMnUXguFIFWlSIlWhBJy+eZBuUY09PU4H3wo7fX++++/+3eKhWRRp9RB3+gwNtMwLScnealDQeAzvsNvWIO1yhdER91yEgxtQjJABv9VrkAVdVVXdlPHwB4HKwLmdQUZNvAR2ItWoxhHEZHciUQxDiL/lftU4tDk1epOzMu5mOWlVG/XNIk/PeFiuOrrQYCqeBbAPA1oY/6S/iAp5z1ULtVGSwO0CogfrSgnYUIlnp1K9TmSBpwJYLYoQNKoQ0v+fi/7YBYDjsA0zAVewOhkZadg1rQKyE3Lj56zMNmZcC0NYrg/3buw7q2Yj12FtRfM8qKdwGOfPQ0pFMid++5OwPpA8dL7J4BQDu73SwAtoEig5xsNL3htAWFCTg13E+rjxGX+eyEwC2N2ENlAG3gCxCDCKCZ9gPDqAXst42KgCdCngJAfAEQfcdfxvOeNAHKqJupn914VsDFJgLuKm4AXjA6y/yaAHKoNkAULnMYyQQB7W+nbgKdzCwm8eJwJYM/2ZzmnBF7BTgRs5TRajFmtR8Kg+TqG4STrdpQb7BFNmDFsUSxys7odyutNV/kCqhARHIOkjrSOXHbIt9/F2zV0xd9KrbYtwFCJSgAAAABJRU5ErkJggg==)**Alpaca Markets API** to to pull historical stocks 
 and bonds information 
 
 And the ![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAACGklEQVR4AWIgBtwKsgP0Xg+wdkRRAEXvt/3D2rbj1LbCmkHNGLVt21Ft27Ztu6e7np7MPCNZ0RvsmVxk/iiHlmhu0QIFYAL+UwHJ2IYv+GjxFTMRgaAG1MBbiI07KIQg3RwYA3HwDV1hEJSAHLgMcWEbEhGUp++IrxAXXqNKMAJisAbigREwCGhAcdyDeOA8siKgr3+ww6D7CFG+oDUMAhKQiaMQ5RFm4zNEWYVoBOTpG+MDRFmP4rgS0DVBBURhEUT5io4wmAix0RcGfgUUxF2Icgk5YFAJzyHKNiTBr9ffA2JjLMxvcVgHUd6inj8BqdjlcOHqMBZ9IDbmIhI+BVTFW4iyEymwHlsYdxwGY2F4ffMwjIPY6A6jAiIwF2KjDwy8CsiJSxDlBvLDbrzUwTuIshVJ3gZ0wDeIMg+RCFfCkIH9rjYohCsGtnN/JcTGWazASge3IDaOqfNWYT7y2QWUxH1ICAyE5ebAEEiI7ECq3ngOQ0LkNRpZAxrjIySEFlkH3xKI8hmXccYLTmPohTruLA7+CciPWw4jvwDSkemBNNTDK4hyDkX0tfTGo01DOLxZR5KwBaJ8REOokyjCTojyBjXgy07aFd8gyhSE4b+Taju8sl1Ihi+bWW5cgyg3UUQHLHG1UPgYEIE5EBu9YPD3hLO4jVu/3cYJFIG/35JX1bXvYQ6irAEFkF/JgQj4+0GTB/mV7NaB/R1d2E1bTr6jywAAAABJRU5ErkJggg==)**Alternative Free Crypto API** to retrieve Bitcoin and Ethereum prices.
 
 
 ### **The first Part is about a Personal Financial Planner**
 ![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQZ5SI2ftHD88BzJkOVZIstPQLiErK7br7SXA&usqp=CAU)

The first will be a personal finance planner that will allow users to visualize their savings composed by investments in shares and cryptocurrencies to assess if they have enough money as an emergency fund.

Collecting Crypto BTC![](https://s2.coinmarketcap.com/static/img/coins/64x64/1.png), ETH![](https://s2.coinmarketcap.com/static/img/coins/64x64/1027.png) prices using the requests Library. Parsin the API JSON response to select only both crypto prices and store their respective prices in a variable.


### **The secord Part is about creating a retirement planning tool using the Alpaca API** 
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTs_2RAjUj-E1rM6WwjHs3YjkDKfjme8GUgYA&usqp=CAU)

A retirement planning tool that uses the Alpaca API to fetch historical closing prices for a retirement portfolio composed of stocks(SPY) and bonds(AGG). Running Monte Carlo simulations to project the portfolio performance at 30 years. Then I used the Monte Carlo data to calculate the expected portfolio returns given a specific initial investment amount.


### **Technologies**
Packages:
* [os] (https://docs.python.org/3/library/os.html)
* [requests] (https://pypi.org/project/requests/)
* [json] (https://docs.python.org/3/library/json.html)
* [dotenv] (https://pypi.org/project/python-dotenv/)
* [alpaca_trade_api] (https://alpaca.markets/docs/)
* [MCForecastTools.py] 



### **Resources**

This project will utilizes two `APIs`:

1. The **Alpaca Markets API**  to pull historical stocks and bonds information. [AlpacaDOCS](https://alpaca.markets/docs/)

2. The **Alternative Free Crypto API** to retrieve Bitcoin and Ethereum prices. [Free Crypto API Documentation](https://alternative.me/crypto/api/)


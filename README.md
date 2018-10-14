## Analyzing correlations between cryptocurrencies and financial markets

Forked originally from triestpa who did an amazing job getting the python scripts to pull in the different data from poloniex and making a great aggregated source of Bitcoin Prices.

The next step for me here is to:

- Bring in more crypto data (the universe and altcoins - not just the top 10)
- Bring in financial data including inices (S&P500, TSX , FTSE100, R2000 etc) and ETF's
- Start to find correlations within industries and map them to cryptocurrencies if we can start to segment them by industry or type of project
- General messing about
- This would be the stretch goal - but making this jupyter notebook into its own API service to start to capture more data
* https://blog.ouseful.info/2017/09/06/building-a-json-api-using-jupyer-notebooks-in-under-5-minutes/
* http://blog.ibmjstart.net/2016/01/28/jupyter-notebooks-as-restful-microservices/

Included in this repository are the
- Jupyter Notebook
- Notebook HTML Page
- Pre-rendered charts (PNG and HTML)

![alt text](https://github.com/kayuzee/Crypto_data/blob/master/charts/png/corr_2016.png)
![alt text](https://github.com/kayuzee/Crypto_data/blob/master/charts/png/corr_2017.png)
![alt text](https://github.com/kayuzee/Crypto_data/blob/master/charts/png/corr_2018.png)

This Python notebook is 100% open-source, feel free to utilize the code however you would like.
```
The MIT License (MIT)

Copyright (c) 2017 Qayyum Rajan

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

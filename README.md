# fintech_budget_retirement_plans

This is a simple prototype to do the following things: 
1. They are able to assess their monthly budgets. 
2. They are able to forecast a reasonably effective retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds.


---

## Technologies

This project uses python 3.7 along with jupyter lab 3.0.14 with the following packages:

* [pandas](https://github.com/pandas-dev/pandas) - For data manipulation and analysis.

* [matplotlib](https://github.com/matplotlib/matplotlib) - For inline data visualizations.

* [requests](https://docs.python-requests.org/en/latest/) - For sending HTTP calls

* [os](https://docs.python.org/3/library/os.html) - For calling environment variables
 
* [json](https://docs.python.org/3/library/json.html) - For viewing api calls in json format

* [dotenv](https://pypi.org/project/python-dotenv/) - For loading in .env file

* [alpaca_trade_api](https://github.com/alpacahq/alpaca-trade-api-python) - For accessing stock/ticker data from alpaca

* [MCForecastTools](included in folder) - For running Monte Carlo Simulations and viewing Simulation data

---

## Installation Guide

Before running the application first install the following dependencies:

```python
$ pip install pandas
$ python -m pip install -U matplotlib
$ python -m pip install requests
$ pip install python-dotenv
```

To install alpaca_trade_api the following dependencies must also be installed:

```
$ pip install pandas==1.1.5 numpy==1.19.4 scipy==1.5.4
$ pip3 install alpaca-trade-api
```
os and json libraries are included in Python 3.7.

---

## Usage

To use this you must have an alpaca_api_key and alpaca_secret_key. To get this register here: https://app.alpaca.markets/signup and then generate api keys copy and paste them into a text editor it should all be for free. Navigate to the folder that contains the jupyter lab file and create a new text file and open it up and set the ALPACA_API_KEY AND ALPACA_SECRET_KEY should be set up as if you are assigning string variables with the keys stored in quotes and then rename the file to .env a hidden file.

You can then go in and edit the tickers/crytocurrencys, bitcoin/stock amounts, and income to your own and then run the code to view the results.

---

## Contributors

Deep Patel --- deep4patel9@gmail.com

---

## License

MIT License
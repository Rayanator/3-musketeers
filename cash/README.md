# 3-musketeers Cash

## Features
- The cash software allow the user to convert currency in real time, using an api  that gives the most updated values of each currencies.

- This software handle 31 different currencies.

|currencies available|
|-------------------------|
|"AUD":| "Australian Dollar"|
|  "RUB":| "Russian Rouble"|
|  "EUR":|"Euro"|
|  "BGN":| "Bulgarian Lev"|
|  "BRL":| "Real Brazilian"|
|  "CAD":| "Canadian Dollar"|
|  "CHF":| "Swiss Franc"|
|  "CNY":| "Chinese Yuan"|
|  "CZK":| "Czech Koruna"|
|  "DKK":| "Danish Krone"|
|  "GBP":|"Pound Sterling"|
|  "HKD":| "Hong Kong Dollar"|
|  "HRK":| "Croatian Kuna"|
|  "HUF":| "Hungarian Forint"|
|  "IDR":| "Indonesian Rupiah"|
|  "ILS":| "Israeli Shekel"|
|  "INR":| "Indian Rupee"|
|  "JPY":| "Japanes Yen"|
|  "KRW":| "South Korean Won"|
|  "MXN":| "Mexican Peso"|
|  "MYR":| "Malaysian Ringgit"|
|  "NOK":| "Norwegian Krone"|
|  "PHP":| "Philippine Peso"|
|  "PLN":| "Polish Zloty"|
|  "RON":| "Romanian New Leu"|
|  "SEK":| "Swedish Krona"|
|  "SGD":| "Singapore Dollar"|
|  "THB":| "Thai Baht"|
|  "TRY":| "Turkish Lira"|
|  "USD":| "US Dollar"|
|  "ZAR":| "South African Rand"|
|  "NZD":| "New Zealand Dollar"|


## Getting Started
After forking the project and git clone it,
git clone https://github.com/YOUR_USER_NAME/3-musketeers.git
You must use `npm install`, in a cmd, to get the packages.

## Prerequisites
You need to have a working packages of node js, with the working parth to your system variables.

## Launch
open a `cmd` and run the index.js script with, `node index.js`

## API

### converts {amount, to, from, response, loading})

Converts an amount from one unit to another unit.

- `from` (number | string | [Big](https://www.npmjs.com/package/big.js)) - the amount to convert
- `fromUnit` (string) - the unit of the amount
- `toUnit` (string) - the unit to convert to
- `representation` (string) - the type of value to return, defaults to 'Number'.
   - 'Number' - returns a standard javascript [Number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)
   -  'Big' - returns a [Big](https://www.npmjs.com/package/big.js) number
   -  'String' - returns a [string](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)



## Commands
You have acces to three commands:
- -s to save a currencies as default currencies.
- -h to display help message
- -v to display the version number

## Default use
```
cd 3-musketeers\cash\bin
node index.js <amount><currency>

```

#### Examples
    eg : node index.js 400 eur \\ return 496.84 (USD) US Dollar


##### Note
Allcaps or lowercaps are both accepted


##### Built With:
- JavaScript
- Node js
- Sublime text editor

###### Requiered packages:
- conf from config


#### Contributing
Please read index.html in out file for details on our code of conduct.

### Versioning
Version `1.0.0`

### Authors
Yassine Azzout,
Rayan Galetta

### License
This project do not have license, as it is open source.

### Acknowledgments
https://fixer.io/     apilayer

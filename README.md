# Exchange-Rate-Board

This Swift code defines a class called ExchangeRate which represents an exchange rate between two currencies. It has four properties: fromCurrency and toCurrency are strings representing the currencies being exchanged, baseAmount is an unsigned integer representing the amount of the base currency being exchanged, and rate is a floating point number representing the exchange rate.

The class has an initializer method that takes in four parameters - the from currency, the to currency, the base amount, and the exchange rate. The initializer sets the class properties with these values.

The class also has a computed property called description which returns a string representation of the exchange rate, including the baseAmount, fromCurrency, rate, and toCurrency.

The code then creates instances of the ExchangeRate class and adds them to an array called exchangeRateTable. The exchangeRateTable array contains a list of exchange rates between various currencies.

Finally, the code loops through the exchangeRateTable array and prints the description of each ExchangeRate instance in the array.

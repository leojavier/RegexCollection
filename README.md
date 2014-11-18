RegexCollection
===============
This is a simple snipet that contains the most common credit cards in the market. Using the javascript function match();
you can validate the card numbers.

Feel free to download the project and run it locally

var visa = /^4[0-9]{12}(?:[0-9]{3})?$/;//All Visa card numbers start with a 4. New cards have 16 digits. Old cards have 13.
var masterCard = /^5[1-5][0-9]{14}$/;//All MasterCard numbers start with the numbers 51 through 55. All have 16 digits.
var amex = /^3[47][0-9]{13}$/;//American Express card numbers start with 34 or 37 and have 15 digits.
var discover = /^6(?:011|5[0-9]{2})[0-9]{12}$/;//Discover card numbers begin with 6011 or 65. All have 16 digits.
var emails = /var emailReg = /^(([^<>()[\]\\.,;:\s@\"]+(\.[^<>()[\]\\.,;:\s@\"]+)*)|(\".+\"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/;/
var cvv = /^[0-9]{3,4}/;//Credit cards security code. from 3 to 4 digits

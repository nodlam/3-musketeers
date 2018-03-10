# CASH MODULE

# Description

The cash module is used to make conversion of different currencies.

# Installation

Fork, then clone the project like this:
-> git clone https://github.com/nodlam/3-musketeers.git

Install the required module/npm dependencie like this:
-> npm install ...

# Usage

First, you can run index.js by doing 
--> node bin/index.js
It will show some functions to run:

For example, execute: 
--> node cash.js 1 USD EUR GBP     (it will convert 1 USD to EUR, GBP..)

To convert an amount from a currency1 to others currency2 and currency3 :
--> node bin/index.js <amount> <currency1> <currency2> <currency3>

To save currencies as default currencies :
--> node bin/index.js --save <currency1> <currency2> <currency3>

For help :
--> node bin/index.js --help

All available currencies to use are shown in currencies.json
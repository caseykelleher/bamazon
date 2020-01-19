# BAmazon

Created during Lesson 10: Node.js & MySQL of UCF Coding Bootcamp. The goal was to create an Amazon-like store front using Node.js and MySQL.

## Getting Started

- Clone repo.
- Run command in Terminal or Gitbash 'npm install'
- Run command depending which mode you would like to be on:
    * Customer - 'node bAmazonCustomer.js'
- Run 'ctrl + c' to exit.

### What Each JavaScript Does

1. `bAmazonCustomer.js`

    * Prints the products in the store.

    * Prompts customer which product they would like to purchase by ID number.

    * Asks for the quantity.

      * If there is a sufficient amount of the product in stock, it will return the total for that purchase.
      * However, if there is not enough of the product in stock, it will tell the user that there isn't enough of the product.
      * If the purchase goes through, it updates the stock quantity to reflect the purchase.
      * It will also update the product sales in the department table.

-----------------------


## Demo Videos

* BamazonCustomer.js (https://youtu.be/07evBHxOqMc)

## Technologies used
- Node.js
- Inquire NPM Package (https://www.npmjs.com/package/inquirer)
- MYSQL NPM Package (https://www.npmjs.com/package/mysql)

### Prerequisites

```
- Node.js - Download the latest version of Node https://nodejs.org/en/
- Create a MYSQL database called 'bAmazon_DB', reference schema.sql
```

## Built With

* VS Code - Text Editor
* MySQLWorkbench
* Terminal/Gitbash
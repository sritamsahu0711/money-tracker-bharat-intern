
# Money Tracker Bharat Intern

### Technology for frontend
•	HTML

•	CSS

### Technology for Backend

•	NodeJS

### Technology for Database

•	MongoDB

## Frontend page

![MONEY TRACKER - Word 02-04-2024 01_24_36](https://github.com/chandrasekharjena-ui/MoneyTracker_bharat_intern/assets/72114961/0c4a749f-7b24-4eb0-8348-43a57bbd743e)

### Add Transaction page

#### •	Description

purpose of investment

#### •	Amount

amount spends for the purpose

#### •	Type

you have incomed the amount or invested

#### •	Add transaction

click on transaction to add the inputted transaction data to the database

![Add Transaction - Personal - Microsoft​ Edge 16-03-2024 02_07_22](https://github.com/chandrasekharjena-ui/MoneyTracker_bharat_intern/assets/72114961/e348822d-8fd6-4dad-a653-f82875f0703e)

### Edit Transaction page

•	In edit transaction user can change or modify the description amount of investment

•	After clicking on the save change update the data to the database

![MONEY TRACKER - Word 02-04-2024 00_39_54](https://github.com/chandrasekharjena-ui/MoneyTracker_bharat_intern/assets/72114961/0148c52e-1cb1-4169-b9c0-448f12d8134e)

### Backend server
#### Dependence for running the application 

•	Nodemon 3.1.0

•	ejs 3.1.9

•	mongoose 8.2.1

•	Body-parser 3.1.0

#### Commands for running the web application
•	To initialisation the Nodejs package
```bash
  npm init
```
•	To install the dependencies
```bash
  npm install express mangoose body-parser ejs nodemon
```
•	To run the server 
```bash
  node server.js
```
![MONEY TRACKER - Word 02-04-2024 00_42_47](https://github.com/chandrasekharjena-ui/MoneyTracker_bharat_intern/assets/72114961/29aa5eb4-2255-4b6b-92c3-220e326dae65)


•	Server start hosting the web page in local host port number (https://localhost:3000) Then in the web browser we can see the web page in given url.

### Database
#### Connection to the MongoDB
•	For connection to database (mangodb://localhost:27017/transactions)

•	After inserting the transactions to the frontend page, it will store the data in the bellow database file.

![MONEY TRACKER - Word 02-04-2024 00_49_18](https://github.com/chandrasekharjena-ui/MoneyTracker_bharat_intern/assets/72114961/fc871e11-0f72-4724-be70-100aca3c19cd)

### How it works

after starting the server in the port number 3000 .in the browser 
URL ->(https://localhost:3000) our frontend page will be displayed. Then the inserted transaction will save in our mongoDB database(mangodb://localhost:27017/transactions) and it will update the transaction after all you edit your transaction

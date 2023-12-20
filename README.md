# ecommerce-backend

## Description

The purpose of this project is to work with Express.js APi, configure, and to use Squalize to interact with MySQL database.

## Installation

To get started clone this repository using 
<br>
```terminal
git clone git@github.com:jxdang1/ecommerce-backend.git
```
Both Node.js and MySQL must be installed on your computer.

Install dependencies 
```terminal
npm init --y
``` 

```terminal
npm i
```

```terminal
npm install express sequelize mysql2
```

Open up MySQL shell and input 
```terminal
source db/schema.sql
```
and 
```terminal
use ecommerce_db
```
Then quit MySQL shell and input the following in your terminal
```terminal
npm start
```
to start running application simply input 
```terminal
node server.js
```
Open up Insomnia core to GET, POST, PUT and DELETE from different routes.

## Usage
The application is used to GET data for each route(categories, products, or tags) as well as create, update, and delete data in those routes. You are able to view a demo of this project [here](https://watch.screencastify.com/v/J4XJ4oF1W2kPas6JHHar)


## Credit

Starter code was provided by KU Full-Stack Bootcamp.

## License

Refer to the license in the GitHub repo
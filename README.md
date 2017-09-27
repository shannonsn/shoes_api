# Shoes API

## Content

  1 What the app is used for
  2 What the API allows you to do
  3 Prerequisites
  4 Dependancies
  5 How to install
  6 Heroku
  7 Issues
  8 How to run the API locally

### What it is used for

  *  Shoe catalogue API is used for accessing the shoes data in a database[MONGO]
  *  Finding shoes with a specific size
  *  Filtering shoes with a specific brand
  *  Filtering the shoe size and shoe brand
  *  Decrementing the shoe stock when a shoe is sold


### What the API allows you to do
  *  The shoe catalogue API allows retrieving from the database [MONGO] of all shoes
  *  Allow new shoes to be added to the database
  *  Allows filtering of data like finding a specific size or brand or both size and brand
  *  The API allow up update of shoes that are already in the database
     by decrementing the stock for a specific shoe when the shoe is sold

### Prerequisites
 ##### PostMan
 go to [Postman](https://www.getpostman.com/) to download(optional)

 ##### NodeJS
 go to [NodeJS](https://nodejs.org/en/) to downlaod

 ##### MongoDB
  go to [Mongo](https://www.mongodb.com/) to download

 ##### Nodemon
 go to [nodemon](https://nodemon.io/) for more detail and how to install

 #### Heroku
 go to [Heroku](https://www.heroku.com/) (optional)

## Issues
There is no "GET" route for creating and posting shoes to the database[Mongo]
(Therefore Postman is used to to act as an Interface)

 ### fork, cloning, or zip the Repository
 * open your CLI(Command Line Interface) and navigate to the shoes_api folder

 * now navigate to the cloned,zipped or forked folder and run:
 ### Installing Dependancies
 run:
 ```
 npm install
```
   * this command will install all neccessary dependancies declared in the package.json file for the app to run

  Now in the same folder in the CLI
 * run command:
 ```
 nodemon
 ```

this should print out an awesome message like:
```
This is where the magic happens : 7070
This is where the awesome takes place

```
 you can now navigate to your prefered browser and insert
```
 localhost: 7070
```
this will load a page with information from the API

```
[{"_id":"59bfae21f74ef21d3dd733c5","color":"blue","brand":"skyline","price":750,"size":4,"in_stock":2,"__v":0},{"_id":"59bfae48f74ef21d3dd733c6","color":"grey","brand":"origin","price":850,"size":3,"in_stock":4,"__v":0}]
```

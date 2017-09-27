# Shoes API

## Content

1. What the app is used for
2. What the API allows you to do
3. Prerequisites
4. Dependancies
5. How to install
6. Issues
7. How to run the API locally

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

* ##### NodeJS

* ##### MongoDB

* ##### Nodemon

* ##### PostMan(this is optional)

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

This should print out an awesome message like:
```
This is where the magic happens : 7070
This is where the awesome takes place
```
 You can now navigate to your prefered browser and run
```
 localhost: 7070
```

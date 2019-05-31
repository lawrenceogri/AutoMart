# AutoMart
[![Build Status](https://travis-ci.org/lawrenceogri/automart.svg?branch=develop)](https://travis-ci.org/lawrenceogri/automart)
[![Coverage Status](https://coveralls.io/repos/github/lawrenceogri/automart/badge.svg?branch=master)](https://coveralls.io/github/lawrenceogri/automart?branch=master)
[![Code Climate](https://codeclimate.com/github/codeclimate/codeclimate/badges/gpa.svg)](https://codeclimate.com/github/lawrenceogri/automart)

Auto Mart is an online marketplace for automobiles of diverse makes, model or body type. With
Auto Mart,  can sell their cars or buy from trusted dealerships or private sellers

---

## User Interface (UI)
* HTML
* CSS
* Javascript

### GitHub Pages link for UI
[AutoMart/UI link](https://raymond42.github.io/Auto-Mart/UI)

---

## SERVER

### API ENDPOINTS

| Ressource URL | Methods  | Description  |
| ------- | --- | --- |
| /api/v1/auth/signup| POST | Get the user to signup |
| /api/v1/auth/login | POST | Get the user to login |
| /api/v1/car | POST | Get the user to post a car sale advertisement |
| /api/v1/order | POST | Get the user to make a purchase order |
| /api/v1/cars/:id/ | PATCH | Get the user to update the price of his/her posted car sale ad |
| /api/v1/order/:id | PATCH | Get the user to update the price or his/her purchase order |
| /api/v1/car/:id | PATCH | Get user to mark his/her posted AD as sold  |
| /api/v1/car/:id | GET | Get user to view a specific car |
| /api/v1/cars/available | GET | Get user to User can view all unsold cars |
| /api/v1/cars/available/range | GET | Get the user to view all unsold cars within a price range |
| /api/v1/cars/posted | GET | Get the Aamin to view all posted ads whether sold or unsold |
| /api/v1/cars/available/used | GET | Get the user to view all used unsold cars |
| /api/v1/cars/available/new | GET | Get the user to view all new unsold cars |
| /api/v1/car/:id | DELETE | Get the admin to delete a posted AD record |

## Used Tools


```
### Server Environment
```
 **NodeJS**
 ```
### Framework
```
 **Express** 
 ```
### Testing Framework and assertion library
```
 **Mocha**
 ```
### Continuous Integration
```
Travis CI
```
### Test Coverage
```
nyc
```
### Git badge
```
coveralls
```
### Deployment
```
Heroku
```
### Heroku link Example


## Getting Started


## Prerequisites


```
 [Node Package Installer - NPM] this usually comes with Node or YARN in case NPM doesn't work.
```

## Installing


```
> npm install
```

It will install the node_modules which will help you run the project on your local machine.

## Run the server
```
> npm start
```
## Run the test
```
> npm test
```


## Author
Lawrence Ajite

---

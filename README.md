# Stonks simulator - trading simulator

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Team](#team)
* [Screenshots](#screenshots)
* [Installation](#installation)
* [Usage](#usage)

# General Information
This app allows you to buy stock actions and sell them at the current price

# Technologies Used
* React with Typescript
* ChakraUI
* Node.js
* MongoDB
* Express

# Features
* Polish and English version
* Light mode/Dark mode
* Mobile friendly

# Team
* [Wojciech Łukowiak](https://github.com/wojtequ) - Front-End
* [Bartosz Kępa](https://github.com/Bartflo) - Front-End
* [Jakub Staszczak](https://github.com/Nasa1x1) - Back-End
* [Juliusz Wiaderek](https://github.com/JWiaderek) - Back-End
* [Mateusz Pawlak](https://github.com/BismarckVonRed) - UI/UX design

# Screenshots
## Landing Page
<img src="https://i.imgur.com/vxvbiK8.png" alt="Landing Page" width="800" height="600">

## Home
<img src="https://i.imgur.com/uTVg4ro.png" alt="Home Page" width="800" height="600">

## Transactions
<img src="https://i.imgur.com/O3rTmqC.png" alt="Transactions Page" width="800" height="600">

## Details
<img src="https://i.imgur.com/Od5XALL.png" alt="Details Page" width="800" height="600">




# Installation
## Front-end installation

### At main folder run:
### `npm install`


## Back-end installation
### `cd backend && npm install`

### Also you have to add your own `.env` file with config to connect mongo, which should be in `\backend` folder

Template `.env`
```
uri= <your_connect_uri_to_mongo>
jwtkey = <your_random_jwtkey>
```

## Usage

### You should start backend and frontend at the same time in two different terminals

### Front-end in main folder you should start with `npm start`
### Backend `cd backend && npm start`

# ECommerce Platform

Explore a user-friendly interface that prioritizes simplicity without compromising on functionality. Our E-commerce MERN (MongoDB, Express.js, React, Node.js) app is designed to make navigation smooth, ensuring a delightful shopping experience for users of all backgrounds.

Easily find the products you're looking for with search and filtering options. Order them with signing in to the account. Having all the options like payment and cart to store the items selected.

[Take tour of ECommerce Application](https://www.loom.com/share/7bfaa651382f46e0959480fec7e662e4)

<!-- toc -->

- [Features](#features)

- [Usage](#usage)

- [Env Variables](#env-variables)

- [Install Dependencies (frontend & backend)](#install-dependencies-frontend--backend)

- [Run](#run)

- [Build & Deploy](#build--deploy)

- [Seed Database](#seed-database)

<!-- tocstop -->

## Features

- Full featured shopping cart

- Product reviews and ratings

- Top products carousel

- Product pagination

- Product search feature

- User profile with orders

- Admin product management

- Admin user management

- Admin Order details page

- Mark orders as delivered option

- Checkout process (shipping, payment method, etc)

- PayPal / credit card integration

- Database seeder (products & users)

## Installation Guide

  

### Requirements

- [Nodejs](https://nodejs.org/en/download)

- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

## Usage

- Create a MongoDB database and obtain your `MongoDB URI` - [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/register)

- Create a PayPal account and obtain your `Client ID` - [PayPal Developer](https://developer.paypal.com/)

```shell

git  clone  https://github.com/Creolestudios/e-commerce_mern.git

cd  e_commerce_mern

```

### Env Variables

Rename the `.env.example` file to `.env` and add the following

```

NODE_ENV = development

PORT = 5000

MONGO_URI = your mongodb uri

JWT_SECRET = 'abc123'

PAYPAL_CLIENT_ID = your paypal client id

PAGINATION_LIMIT = 8

```

Change the JWT_SECRET and PAGINATION_LIMIT to what you want

### Install Dependencies (frontend & backend)

```

npm install

cd frontend

npm install

```

### Run

```



# Run frontend (:3000) & backend (:5000)

npm run dev



# Run backend only

npm run server

```

## Build & Deploy

```

# Create frontend prod build

cd frontend

npm run build

```

### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```

# Import data

npm run data:import



# Destroy data

npm run data:destroy

```

```
Sample User Logins

admin@email.com (Admin)
123456

john@email.com (Customer)
123456

jane@email.com (Customer)
123456
```

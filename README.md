# ShopEZ - MERN Stack Application

ShopEZ is a full-stack e-commerce application built using the MERN stack (MongoDB, Express, React, Node.js) as part of the Naan Mudhalvan project. This application provides a seamless shopping experience for users, allowing them to browse, filter, and purchase products, as well as manage orders. It includes both user and admin functionalities.

## Table of Contents
1. [Project Structure](#project-structure)
2. [Installation](#installation)
3. [Environment Variables](#environment-variables)
4. [Usage](#usage)
5. [Features](#features)
   - [User Features](#user-features)
   - [Admin Features](#admin-features)
6. [Tech Stack](#tech-stack)
7. [Demo Video](#demo-video)

---

## Project Structure

The project is organized into two main folders:
- **client/** - Contains the front-end React code for the application.
- **server/** - Contains the back-end Node.js and Express code.

## Installation

### 1. Clone the Repository
``` bash
git clone https://github.com/JosanGeorge/NM_Mern_Stack-ShopEZ.git
cd NM_Mern_Stack-ShopEZ
```

### 2. Install Dependencies
IGNORE THE ERRORS WHILE INSTALLING, CONTINUE TO RUN THE APPLICATION
#### Server
``` bash
cd server
npm install
```

#### Client
``` bash
cd client
npm install
```

## Environment Variables

Add your own configuration in `.env` in the root of the **server** folder. Here’s an example of the `.env` file:
```
DRIVER_LINK = mongodb+srv://username:password@url/ShopEZ?retryWrites=true&w=majority&appName=Cluster
```

## Usage
IF YOU STILL ENCOUNTER ANY ERRORS WHILE RUNNING THE SERVER OR CLIENT, REMOVE THE NODE_MODULES FOLDER AND RUN `npm install`. NOW TRY AGAIN, IT WILL WORK
### Running the Server
The server runs on port 6001.
``` bash
cd server
node index.js
```

### Running the Client
The client will start on port 3000 by default.
``` bash
cd client
npm start
```

## Features

### User Features
1. **User Registration and Login**:
   - Register as a new user or log in with existing credentials.
   
2. **Product Browsing and Filtering**:
   - Filter products by categories, gender, popularity, price (low to high or high to low), and discount.
   
3. **Shopping Cart**:
   - Add products to the cart and proceed to checkout.
   
4. **Checkout and Order Placement**:
   - Provide details such as name, mobile, email, address, and payment method to place an order.
   
5. **Order Management**:
   - View and cancel orders from the user profile page.

### Admin Features
1. **Admin Login**:
   - Login using admin credentials:
     - **Email**: admin@shopez.com
     - **Password**: admin

2. **User Management**:
   - View the total number of users and their details, including the number of orders placed by each user.
   
3. **Product Management**:
   - Add, update, or remove products.
   - Add products with categories, images, discounts, etc.
   
4. **Order Management**:
   - View all placed orders, update their status (e.g., Order Placed, In Transit, Delivered), and cancel orders if necessary.
   
5. **Banner Management**:
   - Add banners by providing a URL through the admin panel.

## Tech Stack
- **Frontend**: React, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB

## Demo Video
https://drive.google.com/drive/folders/1MGB5gYFvFIgLMBcfhO4q8ITGq3pMut8c

---

Enjoy using ShopEZ!

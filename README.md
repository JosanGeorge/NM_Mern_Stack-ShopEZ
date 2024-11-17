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

![1](https://github.com/user-attachments/assets/26e51f3e-bc82-485f-9e60-09a5491f9f84)


### 2. Install Dependencies
IGNORE THE ERRORS WHILE INSTALLING, CONTINUE TO RUN THE APPLICATION
#### Server
``` bash
cd server
npm install
```

![2](https://github.com/user-attachments/assets/a1d1f003-131c-40f4-a147-b0eb5f390c1a)

#### Client
``` bash
cd client
npm install
```

![3](https://github.com/user-attachments/assets/5aefed41-5559-467c-8e5c-762e3f8c8f27)


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

![4](https://github.com/user-attachments/assets/1d2f2f92-dca5-4f0c-90c0-d61b8db97c8a)

### Running the Client
The client will start on port 3000 by default.
``` bash
cd client
npm start
```

![5](https://github.com/user-attachments/assets/8fc43d92-5936-44d4-a32e-5addd7987214)


## Features

### User Features
1. **User Registration and Login**:
   - Register as a new user or log in with existing credentials.
     
![user reg](https://github.com/user-attachments/assets/f58866b0-5d69-4085-b2ba-4ae55de41681)

![user login](https://github.com/user-attachments/assets/2ca889a2-b5aa-4b89-96af-55f1ab7ee456)
   
2. **Product Browsing and Filtering**:
   - Filter products by categories, gender, popularity, price (low to high or high to low), and discount.
     
![prod filter](https://github.com/user-attachments/assets/141a8dbd-7e50-49be-b6d5-a689deb4d51d)
   
3. **Shopping Cart**:
   - Add products to the cart and proceed to checkout.
     
![prod add cart](https://github.com/user-attachments/assets/ad768c45-ef76-4271-ae61-7bea0edd7ad0)
   
4. **Checkout and Order Placement**:
   - Provide details such as name, mobile, email, address, and payment method to place an order.
     
![checkout details](https://github.com/user-attachments/assets/01fe54cc-dcdb-4ca7-9177-af28063bc3bc)

5. **Order Management**:
   - View and cancel orders from the user profile page.
     
![view and cancel orders](https://github.com/user-attachments/assets/4b60e647-de4d-46c7-967b-d9805e309f4a)


### Admin Features
1. **Admin Login**:
   - Login using admin credentials:
     - **Email**: admin@shopez.com
     - **Password**: admin
       
![admin page](https://github.com/user-attachments/assets/b4012a66-c85a-4b4b-b813-4ac364f441e0)

2. **User Management**:
   - View the total number of users and their details, including the number of orders placed by each user.
     
![admin user info](https://github.com/user-attachments/assets/8dca218b-7022-418c-a173-58f1ff01d556)
   
3. **Product Management**:
   - Add, update, or remove products.
   - Add products with categories, images, discounts, etc.
     
![admin prod page](https://github.com/user-attachments/assets/8b28eba3-735a-42ee-9b6a-0c8772b0b138)

![admin update prod](https://github.com/user-attachments/assets/abe3f063-f292-4b9a-9b5b-22ffc41a4a92)

4. **Order Management**:
   - View all placed orders, update their status (e.g., Order Placed, In Transit, Delivered), and cancel orders if necessary.
     
![admin order placed](https://github.com/user-attachments/assets/99ca1dca-bd99-49b1-ab52-6ba194084520)

5. **Banner Management**:
   - Add banners by providing a URL through the admin panel.
     
![admin banner update](https://github.com/user-attachments/assets/ee4aaddf-4322-4c85-a44e-6000ae6a5b5e)

![banner update](https://github.com/user-attachments/assets/fa993eb3-5068-4bee-98d3-e7f8782967aa)


## Tech Stack
- **Frontend**: React, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB

## Demo Video
- Watch a quick demo showcasing the installation process, as well as the features and functionalities of the ShopEZ Ecommerce Application. The demo will cover both user and admin functionalities.

[[Click Here For The Demo]](https://drive.google.com/file/d/1MYC1tMsTOqXuh5dozuBPEW3iWxyTXhYB/view?usp=drivesdk)


---

Enjoy using ShopEZ!

# Fast React Pizza Co.

## Table of Contents

1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Features](#features)
4. [Technologies Used](#technologies-used)
5. [Installation](#installation)
6. [Contributing](#contributing)

## Introduction

The Fast React Pizza Co.is a web application designed to facilitate the process of ordering pizzas online. This project aims to provide users with a seamless experience for browsing through a menu, adding items to their cart, and placing orders. Built using React.js and Redux Toolkit, this project showcases modern web development practices and utilizes various libraries and APIs for enhanced functionality.

## Project Structure

The project follows a structured directory layout for maintainability and scalability. Here's an overview of the directory structure:

```
FAST-REACT-PIZZA/
├── node_modules/
├── public/
│   └── vite.svg
├── src/
│   ├── features/
│   │   ├── cart/
│   │   │   ├── Cart.jsx
│   │   │   ├── CartItem.jsx
│   │   │   ├── CartOverview.jsx
│   │   │   ├── cartSlice.js
│   │   │   ├── DeleteItem.jsx
│   │   │   ├── EmptyCart.jsx
│   │   │   └── UpdateItemQuantity.jsx
│   │   ├── menu/
│   │   │   ├── Menu.jsx
│   │   │   └── MenuItem.jsx
│   │   ├── order/
│   │   │   ├── CreateOrder.jsx
│   │   │   ├── Order.jsx
│   │   │   ├── CreateItem.jsx
│   │   │   ├── SearchOrder.jsx
│   │   │   └── UpdateOrder.jsx
│   │   └── user/
│   │       ├── CreateUser.jsx
│   │       ├── Username.jsx
│   │       └── userSlice.js
│   ├── services/
│   │   ├── apiGeoconding.js
│   │   └── apiRestaurant.js
│   ├── ui/
│   │   ├── AppLayout.jsx
│   │   ├── Button.jsx
│   │   ├── Error.jsx
│   │   ├── Header.jsx
│   │   ├── Home.jsx
│   │   ├── LinkButton.jsx
│   │   └── Loader.jsx
│   ├── utils/
│   │   └── helpers.js
│   ├── App.jsx
│   ├── index.css
│   ├── main.jsx
│   └── store.js
├── .eslintrc.json
├── .gitignore
├── index.html
├── package-lock.json
├── package.json
├── postcss.config.js
├── prettier.config.cjs
├── tailwind.config.js
└── vite.config.js
```

## Features

The Fast React Pizza Ordering System includes the following features:

- **Menu**: Users can browse through a list of available pizzas and select items to add to their cart.
- **Cart**: Users can view their selected items, adjust quantities, and remove items from the cart.
- **Order**: Users can place new orders, view existing orders, and update order details.
- **User**: Users can create accounts and manage their profile information.

## Technologies Used

- **React.js**: Frontend library for building user interfaces.
- **Redux Toolkit**: State management library for predictable state container.
- **React Router DOM**: Declarative routing for React applications.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **Vite**: Next-generation frontend tooling for fast development.
- **Node.js**: JavaScript runtime for server-side logic.
- **API Geocoding**: Reverse geocoding API for retrieving user addresses.

## Installation

To run the Fast React Pizza Ordering System locally, follow these steps:

1. Clone the repository: `git clone https://github.com/omarhark/fast-react-pizza.git`
2. Navigate to the project directory: `cd FAST-REACT-PIZZA`
3. Install dependencies: `npm install`
4. Start the development server: `npm start`


## Contributing

Contributions to the Fast React Pizza Co. are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

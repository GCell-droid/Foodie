# 🍔 Foodie

A food ordering platform built with React that allows users to browse restaurants, view menus, and manage cart items.

## 🌐 Live Demo

Check out the live application: [Foodie](https://foodie-z3lj.vercel.app/)

## 📝 Description

Foodie is a React-based web application that fetches restaurant data from the Swiggy API. Users can:
- Browse a list of restaurants on the home page
- Click on a restaurant to view its menu
- Add food items to cart
- View the cart total
- Remove items from cart

## ⚙️ Technologies Used

- **React**: Frontend library for building the user interface
- **Redux**: State management for cart functionality
- **Parcel**: Web application bundler
- **Swiggy API**: For restaurant and menu data

## 🚀 Features

- **Restaurant Listings**: Browse through various restaurants
- **Menu Display**: View the menu for each restaurant
- **Cart Management**: Add items to cart, view cart total, remove items from cart
- **Responsive Design**: Works on desktop and mobile devices

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/GCell-droid/Foodie.git
```

2. Navigate to the project directory:
```bash
cd Foodie
```

3. Install dependencies:
```bash
npm install
```

4. Start the development server:
```bash
npm start
```

## ⚠️ Important Note

This application uses the Swiggy API which has CORS restrictions. To run the application properly:
- Install a CORS browser extension like [CORS Unblock](https://chrome.google.com/webstore/detail/cors-unblock/lfhmikememgdcahcdlaciloancbhjino)
- Enable the extension when using the application

## 📂 Project Structure

```
Foodie/
├── src/
│   ├── components/        # React components
│   ├── redux/             # Redux store configuration and slices
│   ├── App.js             # Main application component
│   └── index.js           # Entry point
├── .gitignore
├── package.json
└── README.md
```

## 📱 Usage

1. Open the application in your browser
2. Enable the CORS plugin
3. Browse through the list of restaurants on the home page
4. Click on a restaurant to view its menu
5. Add items to your cart
6. View your cart and manage items

## 🔄 State Management

Redux is used to manage the cart state across the application. The cart data persists during the session, allowing users to navigate between pages while maintaining their cart items.

## 👨‍💻 Author

- [GCell-droid](https://github.com/GCell-droid)


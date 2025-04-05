# Movie Shop

A React-based movie shopping website where users can search for movies, add them to the cart, apply discounts, and checkout with a countdown timer for payment.

## Features
- **Search for movies** using The Movie Database API.
- **Add price for each movie** and allow customization.
- **Add movies to cart**, with functionality to increase/decrease quantities.
- **Discounts**: 10% off for more than 3 items and 20% off for more than 5 items in the cart.
- **Persistent cart**: When you close and reopen the website, your cart will still be intact.
- **Clear Cart**: Option to clear the cart at any time.
- **Checkout Popup**: When attempting to checkout, a popup shows payment instructions with a countdown timer.

## Requirements
- Node.js (version 14.x or higher)
- npm (version 6.x or higher)

## Setup Instructions

### 1. **Sign up for The Movie Database API**
- Go to [TMDB](https://www.themoviedb.org/) and sign up for an account.
- After signing in, navigate to the [API section](https://www.themoviedb.org/settings/api).
- Copy your **API Key** from the API settings page.

### 2. **Clone the Repository**
Clone the repository to your local machine:
bash
git clone https://github.com/ZulfaBueraheng/MovieShop.git

### 3. Install Dependencies 
Navigate to the project directory:
cd movie-shop
Install all required dependencies:
npm install

### 4. Set up Environment Variables 
Create a .env file in the root of the project and add your TMDB API key:
REACT_APP_TMDB_API_KEY=your-api-key

### 5. Running the Project 
Start the development server:
npm start

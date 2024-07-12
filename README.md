# rn-assignment7-11135584
## Overview

This React Native project demonstrates a basic e-commerce application with the following features:
- A list of available products fetched from an external API.
- Detailed view of each product.
- Adding and removing products from a shopping cart.
- Persisting cart items using local storage.

## Features

### HomeScreen
- Displays a list of available products.
- Each product item includes an "Add to Cart" button.

### ProductDetailScreen
- Shows detailed information about a selected product.
- Includes an "Add to Cart" button.

### CartScreen
- Displays the list of products added to the cart.
- Each cart item includes a "Remove from Cart" button.

### Navigation
- A drawer component/navigation menu accessible through a swipe gesture or button, allowing navigation between screens.

## Implementation Details

### Fetching Data
- Data is fetched from an external API using the `fetch` method or `axios` library.
- Asynchronous operations are managed with `async/await` syntax to handle promises.

### Local Storage
- Selected items are stored locally on the device using AsyncStorage.
- This ensures that the cart persists even if the app is closed and reopened.

### Navigation
- React Navigation is used to handle navigation between screens.
- A drawer navigator provides easy access to different parts of the application.

## Screenshots
![HomeScreen](https://github.com/user-attachments/assets/299eb176-3e89-425d-9f0e-5ab81e3b7011)

![ProductDetailScreen](https://github.com/user-attachments/assets/185c5717-66fa-4246-936b-7434df85d45a)

![CartScreen](https://github.com/user-attachments/assets/cf6085d0-dc8d-4a3e-93db-ed8166de5582)




## Design Choices
- **UI Layout**: The design is kept simple and intuitive, following the provided UI mockup to ensure usability.
- **Local Storage**: AsyncStorage is used for its simplicity and integration with React Native.
- **Error Handling**: Basic error handling is implemented for API calls and local storage operations to enhance user experience.


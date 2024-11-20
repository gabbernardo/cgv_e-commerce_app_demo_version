# CGV E-Commerce App

![Screen_Recording_20241120-152918-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/f1fa2eef-e0a5-4016-a2bb-097ba3cf31cf)


**CGV** is a sleek and minimalist e-commerce application built with **Flutter**, leveraging **dummyjson.com** as the data source. The app is designed with a focus on seamless navigation, performance, and a smooth user experience. The development follows best practices with **Clean Architecture**, **Test Driven Development (TDD)**, and is equipped with advanced features like **BLoC** for state management, **Go_Router** for routing, and **Dio** for HTTP requests.

## Features

- **Splash Screen**: Displayed when the app loads, providing a smooth animation using **Lottie** while the app initializes.
- **Product Dashboard**: Dynamic product display with smooth **pagination** for browsing.
- **Search Functionality**: Easily search products by name or browse through **suggested categories**.
- **Product Details Screen**: View detailed information for each product, including high-resolution images, descriptions, and ratings.
- **Responsive Navigation**: With **Go_Router**, users can seamlessly navigate between different screens.

## Tech Stack

### Software Architecture
- **Clean Architecture**: Ensures separation of concerns by organizing the app into layers (Presentation, Domain, and Data).

### State Management
- **BLoC**: Provides robust state management by using streams and sinks, separating the UI from business logic.

### HTTP Requests
- **Dio**: Used for making HTTP requests, handling API calls efficiently with support for interceptors, error handling, and timeout configuration.

### Routing
- **Go_Router**: Streamlines navigation and routing, providing clear and consistent paths for user journeys.

### Animations
- **Lottie**: Used for smooth animations, enhancing the overall user experience, especially on the splash screen.

---

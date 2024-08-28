# Shopping App - Android E-commerce Application

## Introduction

"Shopping App" is an Android-based e-commerce application designed to provide a seamless shopping experience for users. The application targets the online fashion retail market, offering a wide range of products across various categories such as Casuals, Ethnic, Dresses, Jeans, Shorts, Skirts, Footwear, Mobile, and Watches. The application aims to cater to both Customers and Admins, ensuring a user-friendly interface that simplifies the shopping and management processes.

## Features

### Customer Features
- **Sign Up & Sign In:** Users can create an account or log in to an existing one. The "Remember Me" feature allows customers to stay logged in even after exiting the app.
- **Product Browsing:** Customers can browse products by categories and view detailed information including name, image, description, and price.
- **Search Products:** Search functionality allows users to find specific products quickly.
- **Cart Management:** Customers can add products to their cart, edit quantities, or remove items before placing an order.
- **Order Placement:** After finalizing the cart, customers can place orders by providing their shipping details.
- **Account Settings:** Users can update their profile details such as name, password, and address.

### Admin Features
- **Admin Login:** Admins have a separate login, and they cannot create accounts through the app for security reasons. Admin accounts are pre-approved and managed via Firebase DB.
- **Product Management:** Admins can add new products to the store, categorize them, and provide all relevant details.
- **Order Management:** Admins can view and process customer orders, marking them as complete once shipped.

## System Architecture

The application mimics the architecture of popular e-commerce apps like Amazon, eBay, and Myntra, with a focus on simplicity and efficiency. It leverages Firebase for backend services, providing a robust database and real-time data syncing capabilities.

## Implementation

### Software Requirements
- **Language:** Java
- **IDE:** Android Studio
- **Database:** Google Firebase
- **Minimum Android Version:** Android 12.0 (Snow Cone) and above

### Hardware Requirements
- **Platform:** Android mobile phones or equivalent emulators

### Key Modules
- **Sign Up/Sign In**
- **Product Search**
- **Cart Activity**
- **Order Placement**
- **Settings Management**
- **Product Management (Admin)**
- **Order Processing (Admin)**

## Screenshots



<div style="display: flex; flex-wrap: wrap; gap: 20px;">

  <div style="flex: 1; min-width: 300px; text-align: center;">
    <h3 style="margin-top: 20px; margin-bottom: 10px; font-weight: bold;">Main Activity</h3>
    <img src="https://github.com/arjunnrajput/Shop-Online/blob/38151558f87a5ec5068d0bcf9c69b7f6c7792cee/Screenshots/Main.jpg" width="300" alt="Main Screen Image" style="max-width: 100%; height: auto;">
  </div>

  <div style="flex: 1; min-width: 300px; text-align: center;">
    <h3 style="margin-top: 20px; margin-bottom: 10px; font-weight: bold;">Sign Up</h3>
    <img src="https://github.com/arjunnrajput/Shop-Online/blob/38151558f87a5ec5068d0bcf9c69b7f6c7792cee/Screenshots/registraion.jpg" width="300" alt="Sign Up Screen Image" style="max-width: 100%; height: auto;">
  </div>

  <div style="flex: 1; min-width: 300px; text-align: center;">
    <h3 style="margin-top: 20px; margin-bottom: 10px; font-weight: bold;">Login</h3>
    <img src="https://github.com/arjunnrajput/Shop-Online/blob/38151558f87a5ec5068d0bcf9c69b7f6c7792cee/Screenshots/Customer_login.jpg" width="300" alt="Login Screen Image" style="max-width: 100%; height: auto;">
  </div>

  <div style="flex: 1; min-width: 300px; text-align: center;">
    <h3 style="margin-top: 20px; margin-bottom: 10px; font-weight: bold;">Home Screen</h3>
    <img src="https://github.com/arjunnrajput/Shop-Online/blob/38151558f87a5ec5068d0bcf9c69b7f6c7792cee/Screenshots/IMG-20240822-WA0003%20(1).jpg" width="300" alt="Home Screen Image" style="max-width: 100%; height: auto;">
  </div>

  <div style="flex: 1; min-width: 300px; text-align: center;">
    <h3 style="margin-top: 20px; margin-bottom: 10px; font-weight: bold;">Product Details</h3>
    <img src="https://github.com/arjunnrajput/Shop-Online/blob/38151558f87a5ec5068d0bcf9c69b7f6c7792cee/Screenshots/IMG-20240822-WA0006%20(1).jpg" width="300" alt="Product Details Screen Image" style="max-width: 100%; height: auto;">
  </div>

  <div style="flex: 1; min-width: 300px; text-align: center;">
    <h3 style="margin-top: 20px; margin-bottom: 10px; font-weight: bold;">Cart Activity</h3>
    <img src="https://github.com/arjunnrajput/Shop-Online/blob/433720f5a3a1b748791000ce1e06c7b953f7e08c/Screenshots/IMG-20240822-WA0007%20(1).jpg" width="300" alt="Cart Activity Screen Image" style="max-width: 100%; height: auto;">
  </div>

  <div style="flex: 1; min-width: 300px; text-align: center;">
    <h3 style="margin-top: 20px; margin-bottom: 10px; font-weight: bold;">Admin Dashboard</h3>
    <img src="https://github.com/arjunnrajput/Shop-Online/blob/38151558f87a5ec5068d0bcf9c69b7f6c7792cee/Screenshots/IMG-20240822-WA0008%20(1).jpg" width="300" alt="Admin Dashboard Screen Image" style="max-width: 100%; height: auto;">
  </div>

  <div style="flex: 1; min-width: 300px; text-align: center;">
    <h3 style="margin-top: 20px; margin-bottom: 10px; font-weight: bold;">Order Management</h3>
    <img src="https://github.com/arjunnrajput/Shop-Online/blob/38151558f87a5ec5068d0bcf9c69b7f6c7792cee/Screenshots/IMG-20240822-WA0010%20(1).jpg" width="300" alt="Order Management Screen Image" style="max-width: 100%; height: auto;">
  </div>

</div>


## Conclusion

"Shop Online" successfully delivers an intuitive and functional mobile application tailored to the needs of an online fashion store. The app efficiently handles both customer shopping experiences and admin product management, making it a comprehensive solution for e-commerce in the fashion industry.

## Future Scope

As e-commerce continues to grow, there are numerous opportunities to expand the capabilities of the "Shop Online" application, including integrating advanced features like AI-driven product recommendations, expanding to multiple platforms, and enhancing user engagement through loyalty programs.

## References

1. [Picasso - Image Downloading and Caching Library for Android](https://github.com/square/picasso)
2. [Material Design Components for Android](https://github.com/rey5137/material)
3. [Paper - NoSQL-like Storage for Java/Kotlin](https://github.com/pilgr/Paper)
4. [ElegantNumberButton - Number Counter for Android](https://github.com/ashik94vc/ElegantNumberButton)
5. [Android Image Cropper Library](https://github.com/ArthurHub/Android-Image-Cropper)
6. [Circle ImageView for Android](https://github.com/hdodenhof/CircleImageView)

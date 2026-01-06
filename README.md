# E-Commerce-App-Jetpack-Compose

- A E-Commerce Android application built using Jetpack Compose, following clean architecture principles and modern Android development best practices, and provides a smooth and intuitive shopping experience, allowing users to browse products, manage their cart, and complete payments efficiently.


## ✨ Features >>

### 🔐 Authentication
- User login & registration and Secure authentication flow.

### 🚀 Splash
- Initial app loading screen and Navigation based on user state.

### 🏠 Home
- Browse products and Featured and recommended items.

### 🔍 Search
- Search for products and Filter and discover items easily.

### 📄 Product Details
- View product images and descriptions and Price and availability details.

### ❤️ Favorites
- Add/remove products from favorites and Persist favorite items.

### 🛒 Cart
- Add products to cart, Update quantity or remove items and View total price.

### 💳 Payment
- Complete checkout process By <b><i>PayMob</i></b>
- PaymentMethodScreen {Credit Card / Wallet} , Handle payment success & failure and Payment result screen.

### 👤 Profile
- View and manage user profile and Account-related actions.

### 🧩 Common
- Reusable UI components and Shared composables and utilities.


## 🛠️ Technologies Used::
- language: Kotlin </br>
- UI layouts using Jetpack Compose </br>
- Multi-screen by navigation compose </br>
- Material 3 </br>
- lottie animation  </br>
- Coil Compose  </br>
- Clean Architecture {presentation - domain - data} </br>
- MVVM/MVI architecture </br>
- Retrofit2 & Gson - construct the REST APIs. </br>
- Firebase (Authentication - Firestore Database)  </br>
- Room Database </br>
- Dependency injection by (Dagger Hilt) </br>
- ViewModel & StateFlow </br>
- Coroutines / Flow for asynchronous </br>
- Integration Payment Gateway By (<b><i>PayMob</i></b>)
- Unit Testing  </br>
- Mocking (mockk)  </br>




## Architecture
The following diagram shows all the modules and how each module interact with one another after. This architecture using a layered software architecture.  <br>
<p align="center">
<img src="https://user-images.githubusercontent.com/72816466/202196876-39bb8b5d-aa81-4693-8a5e-b1b588133975.jpeg"/>
  <img src="https://github.com/user-attachments/assets/a2797910-e4df-4c8a-9d40-4455d88826e5"/>
</p>  <br> 


## Libraries Used 📚
- Jetpack Compose: Modern UI toolkit for building native Android UIs.
- Products API: Provides access to products and categories information.
- Paymob API: Handles secure payment processing, transactions, and payment status verification.
- Retrofit: Type-safe HTTP client for Android and Java.
- Firebase: Provides backend services such as authentication, firestore database.
- MVVM/MVI Architecture: Separates UI, business logic, and data management for easy maintainability.
- Dagger-Hilt: Reduces the boilerplate of manual dependency injection.
- Room Database: Local persistence for saving favorite movies.
- Navigation Compose: Handles app navigation in a declarative way.
- Coil: To load image from server to UI.

---
Thanks for checking out the E-Commerce App! Don't forget to ⭐ the repository if you find it helpful. 😊

---
Made with ❤️ by [Mohamed Ra'afat](https://github.com/Mohamed-Rafat-Safan)

---

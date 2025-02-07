# Flutter_StoryNest


# Features of the Bookstore App - StoryNest 📚

The StoryNest bookstore app is designed to provide users with a seamless book-buying experience. Below are its key features:

🌟 1. Home Page (Book Catalog)

Displays a grid of books with their title, author, price, and cover image.
Users can browse through available books and select their favorites.
Implemented using GridView.builder for a smooth scrolling experience.

🛒 2. Shopping Cart

Users can add books to the cart with a single tap.
The cart page displays the selected books, price, and author details.
Users can remove books from the cart before proceeding to checkout.
A "Buy Now" button confirms the purchase.

👤 3. User Profile

Users can set and save their profile details (name and email).
Option to upload a profile picture from the device gallery.
Data persistence using SharedPreferences, so user details remain saved even after closing the app.

🎨 4. Clean & Intuitive UI

Bottom Navigation Bar for easy switching between Home, Cart, and Profile pages.
Consistent color theme (Indigo & Grey) for a visually appealing interface.
Elevated Cards & Buttons to enhance the app’s aesthetics.

⚡ 5. State Management with Provider

Provider package is used to manage cart functionality efficiently.
Ensures real-time updates when books are added or removed from the cart.

💾 6. Persistent Data Storage

SharedPreferences stores user profile data, so it remains after app restarts.
Profile images are saved using local file paths.

🔔 7. User Notifications & Feedback

Snackbars provide confirmation messages when actions (e.g., adding books to the cart, saving profile) are completed.
Alerts and dialogs confirm purchase transactions before proceeding.

🚀 8. Optimized Performance

Lazy loading images to improve speed and memory efficiency.
Efficient use of SliverGridDelegate for smooth scrolling.

# Demo

![Alt Text](https://github.com/GeethDasanayakeGD/Flutter_bookStoer-StoryNest-/Demo.gif)

# Installation 🚀

Clone the Repository

git clone (https://github.com/GeethDasanayakeGD/Flutter_bookStoer-StoryNest-.git)
cd flutter_book_store

Install Dependenciesy

flutter pub get

Run the Appy

flutter run

 

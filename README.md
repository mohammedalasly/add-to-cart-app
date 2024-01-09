# Firebase - Shopping List App 🛒🛍️

This is a simple web application that allows users to create and manage a shopping list using Firebase Realtime Database. Users can add items to the list, mark items as purchased, and remove items from the list.

## Code Demo:

1. Import Firebase SDK modules for app initialization and database operations.
2. Initialize the Firebase app with configuration settings.
3. Set up references to the database and a specific location for the shopping list.
4. Retrieves HTML elements (input field, button, list, error message) for interaction.
5. Listens for button clicks to add items to the shopping list.
6. Listens for changes in the database and updates the UI with the current shopping list.
7. Defines functions to clear the shopping list, input field, and append items to the list.

In summary, the code initializes Firebase, manages a shopping list in the database, and provides a user interface for adding and interacting with items in the list.

## Getting Started 🧑🏾‍💻

to set up a basic Firebase project for managing a shopping list using JavaScript.

1. Clone the repository or download the code files.
2. Open the HTML file (index.html) in a web browser.
3. Create a Firebase Project:

Go to the Firebase Console (https://console.firebase.google.com/) and create a new project.
In the project dashboard, click on "Add project" give your project name in thins case it's called "shoppingList".
After creating the project, Firebase will generate a configuration object(link) with your project's credentials. Copy this configuration object.

In your **JavaScript** file, replace " **_add your own Firebase project link here_** " with the Firebase configuration object you copied earlier.

## Usage

- Enter the name of the item you want to add to the shopping list in the input field.
- Click the "Add Item" button to add the item to the list. If the input field is empty, an error message will be displayed.
- The added items will be listed with the option to mark an item as purchased or remove it from the list.
- When you click on an item, it will be removed from the list and Firebase Realtime Database.

## Live link: 🌐

- [https://add-to-cart-mohammad.netlify.app/](https://add-to-cart-mohammad.netlify.app/)

![shopping boy](/assets/add-to-cart.png)

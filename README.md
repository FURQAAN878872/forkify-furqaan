# 🍴 Forkify – Recipe Application

A feature-rich recipe application built with **modern JavaScript**, following the **MVC (Model–View–Controller) architecture**.

Forkify is more than a recipe website—it is a practical JavaScript application designed to demonstrate how **API communication, asynchronous JavaScript, application state, DOM rendering, event handling, local storage, and modular architecture** work together in a real-world project.

## 🚀 Live Demo

[View Forkify Live](YOUR_LIVE_DEMO_URL)

## 📌 Features

* 🔎 **Recipe Search**

  * Search for recipes using the Forkify API.
  * Dynamically displays matching recipes.

* 🍕 **Recipe Details**

  * Displays detailed recipe information.
  * Shows ingredients, cooking time, servings, publisher, and recipe metadata.

* 📄 **Pagination**

  * Displays search results page by page.
  * Allows users to navigate through multiple recipe results.

* 👥 **Serving Adjustment**

  * Dynamically adjusts ingredient quantities according to the selected number of servings.

* ❤️ **Bookmarks**

  * Save favorite recipes to bookmarks.
  * Persist bookmarked recipes using Local Storage.
  * Access saved recipes even after reopening the application.

* ➕ **Custom Recipe Upload**

  * Allows users to add their own recipes.
  * Uploaded recipes are integrated into the application state.

* 🛒 **Ingredients / Shopping List**

  * Select recipe ingredients for shopping.
  * Manage required ingredients while preparing recipes.

* 🔄 **Dynamic UI Updates**

  * Updates the interface based on user actions and application state.
  * Uses JavaScript to dynamically render application content.

* ⚡ **Asynchronous API Communication**

  * Fetches recipe data from the Forkify API.
  * Handles asynchronous operations using modern JavaScript patterns.

## 🧠 Application Architecture

The application follows an **MVC architecture** that separates application data, user interface rendering, and application control logic.

### Application Flow

```text
User
  ↓
View
  ↓
Controller
  ↓
Model
  ↓
Forkify API
  ↓
Model
  ↓
Controller
  ↓
View
  ↓
UI
```

This structure helped me understand how a larger JavaScript application can be divided into independent responsibilities instead of keeping all logic inside a single file.

## 🏗️ MVC Architecture

### Model

Responsible for:

* API requests
* Recipe data
* Application state
* Bookmarks
* Custom recipes
* Local Storage
* Data transformations

### View

Responsible for:

* Rendering recipes
* Rendering recipe details
* Rendering bookmarks
* Rendering pagination
* Handling UI-related interactions

### Controller

Responsible for:

* C

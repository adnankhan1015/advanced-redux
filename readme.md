# REDUC DEEP DIVE

- Handling **Async Tasks** with Redux
- Wher to **Put Your Code**
- The Redux **DevTools**

1. Redux & Side Effects (and Asynchronous Code)

- Reducers must be **pure, side-effect free, synchronous** functions
  <img src="./src/assets/images/advance-redux-1.png>

### Using Firebase as a Backend

we'll use a third-party service called [Firebase](https://firebase.google.com/) as a dummy backend.

You can get started with Firebase for free - all you need is a Google account.

Then, once logged in with Google, you can create a new project with the default settings. Though you can disable "Google Analytics".

Thereafter, click "Build" and select "Realtime Database" and click "Create Database".

The region doesn't matter but make sure to create the database in "Test mode"!

This will create the database with a connected REST API that we'll use throughout this section.

You can then use the URL displayed on the screen in your React code to send requests to that database.

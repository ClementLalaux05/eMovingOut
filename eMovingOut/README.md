# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### Firebase Config

To run the project , you need :
    
    - to create a firebase project, add Realtime Database and add Authentification 

    - to create a file in /src named firebaseConfig.js and create in it :

export const BASE_DB_URL = "YOUR FIREBASE DATABASE URL"

export const SIGN_IN_URL = `https://identitytoolkit.googleapis.com/v1/accounts:signInWithPassword?key=API_KEY`

export const SIGN_UP_URL = `https://identitytoolkit.googleapis.com/v1/accounts:signUp?key=API_KEY`
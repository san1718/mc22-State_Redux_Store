# State: The Redux Store You Need

## Table of Contents
* [Overview](#overview)
* [Features](#features)
* [Technologies Used](#technologies-used)
* [Installation / Usage](#installation--usage)
* [Testing](#testing)
* [Summary](#summary)
* [Links](#links)
* [Screenshots](#screenshots)

## Overview
This application is an e-commerce platform built using Redux for global state management, replacing the Context API.
By leveraging Redux, the platform ensures efficient, scalable, and predictable state management, improving performance and maintainability for large-scale applications.
This approach decouples the state management from the React ecosystem, allowing for better flexibility and optimization.

## Features
* **Global State Management with Redux**: Efficiently manage global state across the application with a centralized Redux store.
* **Redux Provider**: Uses the Redux provider to inject the store into the React component tree.
* **Reducers**: Implements reducers to handle state changes, making the state management more predictable and testable.
* **Asynchronous Actions**: Handles API requests and asynchronous operations using Redux middleware (e.g., Thunk or Saga).
* **Seamless Integration with React**: Uses React-Redux hooks (`useDispatch`, `useSelector`) for accessing and updating the state from components.
* **Customizable Store**: Easily extendable Redux store for additional features like user authentication, cart management, etc.


## Technologies Used
* **Front-End:**
    * React.js
    * Axios
    * Webpack/Babel
* **Back-End:**
    * Node.js
    * Express.js
    * MongoDB
    * Mongoose
* **Authentication:**
    * [JSON WEB TOKEN (JWT)](https://jwt.io/)
* **Testing:**
    * Jest

## Installation / Usage
1. **Clone Repository:**
    ```bash
    git clone git@github.com:san1718/mc22-State_Redux_Store.git
    ```
2. **Install Dependencies:**
    ```bash
    npm install
    ```
3. **Run the Server:**
    ```bash
    npm run develop
    ```
4. **Open browser and navigate to:**
    * [localhost:3000](http://localhost:3000)

## Testing
1. **Install Dependencies:**
    ```bash
    npm install
    ```
2. **Run Tests:**
    - Jest:
      ```bash
      npm run test
      ```
    - Mocha:
      ```bash
      npm run test:server
      npm run test:client
      ```
3. **Running Tests in Development Mode:**
    ```bash
    npm run develop
    ```
4. **(Optional) Test Coverage:**
    ```bash
    npm run test -- --coverage
    ```

### Example `package.json` scripts:
```json
"scripts": {
  "test": "jest",
  "test:coverage": "jest --coverage"
}
```

## Summary
This e-commerce platform demonstrates how to implement Redux for managing global state, replacing the more common Context API. 
By using Redux, the application benefits from improved performance, maintainability, and flexibility, especially as the application scales. 
The use of reducers, actions, and a central store makes state transitions predictable and easier to debug, enhancing the developer experience.

## Links
[Home](https://github.com/san1718/mc22-State_Redux_Store)
<br />
[Try it! (Live Demo)]()

## Screenshots
<img width="1000" alt="" src="">
<img width="1000" alt="" src="">
<img width="1000" alt="" src="">

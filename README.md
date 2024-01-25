## Prerequisites

Ensure you have the Node.js installed on your machine, preferably the LTS version:

- [Node.js](https://nodejs.org/)

In the project directory, enter the following code to initialize the Node.js:

    ```
    npm init
    ```

## Packages

Install the following packages to run the program successfully:

1. **Phaser**
    
    Phaser is a fast and robust 2D game framework for JavaScript. It provides tools for handling graphics, physics, input, and more, making it ideal for developing interactive games.

    ```
    npm install phaser
    ```

2. **Express**

    Express is a minimal and flexible Node.js web application framework that provides a set of features for web and mobile applications. It facilitates the creation of robust APIs and web servers.

    ```
    npm install express
    ```

3. **Socket.io**

    Socket.io enables real-time, bidirectional, and event-based communication. It is commonly used for building interactive and dynamic applications with WebSocket support.

    ```
    npm install socket.io socket.io-client
    ```

4. **Webpack**

    Webpack is a module bundler that takes your JavaScript, CSS, and other assets, and bundles them together in a way that's optimized for the web. It's often used for building and managing complex front-end projects.

    ```
    npm install webpack webpack-cli
    ```

5. **Nodemon (recommended)**

    Nodemon is a utility that monitors for changes in your source code and automatically restarts the server. It's particularly useful during development, providing a streamlined development experience.

    ```
    npm install nodemon
    ```

## Usage

Build and bundle your Phaser files with Webpack by executing the following command:

    ```
    npx webpack
    ```

Subsequently, initiate the server using:

    ```
    npm start
    ```

While the server is active, access the client in your browser by navigating to:

    ```
    http://localhost:3000
    ```

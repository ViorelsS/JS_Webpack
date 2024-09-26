# Webpack Joke Generator

This project is a simple web application that fetches and displays random jokes using the [icanhazdadjoke](https://icanhazdadjoke.com/) API. The project is built using Webpack, Babel, and Sass.

## Table of Contents

-   [Installation](#installation)
-   [Usage](#usage)
-   [Development](#development)
-   [Build](#build)
-   [License](#license)

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/ViorelsS/JS_Webpack.git
    cd JS_Webpack
    ```

2. Install the dependencies:
    ```sh
    npm install
    ```

## Usage

To start the application in development mode, run:

npm run dev

This will start a development server and open the application in your default web browser.

Development
The main source files are located in the src directory:

-   **src/index.js**: The entry point of the application.
-   **src/generateJoke.js**: Contains the function to fetch and display jokes.
-   **src/styles/main.scss**: The main stylesheet for the application.
-   **src/template.html**: The HTML template used by HtmlWebpackPlugin.

## Build

To build the project for production, run:

The output will be in the dist directory.

### License

This project is licensed under the MIT License.

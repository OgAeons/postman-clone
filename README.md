# Postman Clone

A simple Postman clone built with Vite, Axios, and Codemirror. This tool allows users to make HTTP requests (GET, POST, etc.) and view formatted responses in a clean and interactive interface.

## Features
- **HTTP Request Support**: Send GET, POST, PUT, PATCH, and DELETE.
- **Request Configuration**: Add query parameters, request headers, and a request body.
- **Formatted Response**: View well-structured JSON responses using CodeMirror.
- **Bootstrap Integration**: Responsive UI for an intuitive user experience.
- **Dynamic Metrics**: View response time, status, and size.
- **Axios for Requests**: Efficient handling of API calls.

## Installation
1. **Clone the Repository**  
   `git clone https://github.com/OgAeons/postman-clone.git`  
   `cd postman-clone`
2. **Install Dependencies**  
   `npm install`
3. **Start the Development Server**  
   `npm run dev`

## Usage
1. **Enter a Request URL**  
   Example: `https://jsonplaceholder.typicode.com/todos/1`.
2. **Select the HTTP Method**  
   Example: `GET`, `POST`, `PUT`, `PATCH`, or `DELETE`.
3. **Configure the Request**  
   - **Query Parameters**: Add key-value pairs.  
   - **Headers**: Add custom headers.  
   - **Request Body**: Use the integrated JSON editor for `POST`/`PUT` requests.
4. **Submit the Request**  
   - View the response details, including status, headers, response time, and size.

## Dependencies
- **[Vite](https://vitejs.dev/)** - A fast build tool for modern web applications.
- **[Axios](https://axios-http.com/)** - A promise-based HTTP client for making API requests.
- **[Bootstrap](https://getbootstrap.com/)** - A popular frontend framework for responsive and modern designs.
- **[Codemirror](https://codemirror.net/)** - A versatile code editor used for JSON formatting in this project.
- **[Pretty-Bytes](https://github.com/sindresorhus/pretty-bytes)** - A utility to convert bytes into a human-readable format.
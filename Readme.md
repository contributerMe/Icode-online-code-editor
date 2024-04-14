# Online Code Editor with Server-Side Compilation

I-code is a online code editor that supports editing and execution of code in C++, Java, C, and Python. The project uses Express.js along with `body-parser` for handling HTTP requests and `compilex` for server-side code compilation and execution.
Website id deployed on FireBase : https://i-code-online-compiler.web.app/

## Features

- **Syntax Highlighting**: Supports syntax highlighting for C++, Java, C, and Python.
- **Code Execution (Server-Side)**: Compiles and executes code on the server for C++, Java, and C, and uses Skulpt for Python code execution in the browser.
- **Responsive Design**: Built using Bootstrap for a responsive layout across different devices.
- **Language Selection**: Users can choose the programming language they want to work with.
- **Dark/Light Theme**: Toggle button to switch between dark and light themes.(To be implemented)
- **Error Handling**: Displays compilation errors or runtime errors returned by the server.

## Technologies Used

- HTML, CSS
- JavaScript
- Node.js
- Express.js
- Bootstrap
- CodeMirror (for syntax highlighting and text editor features)
- `body-parser` (middleware for parsing incoming request bodies)
- `compilex` (for compiling and executing code on the server)


## How It Works

1. **Frontend**: The frontend (HTML, CSS, JavaScript) handles user interactions and sends code along with the selected programming language to the server via HTTP POST requests.

2. **Server-Side Compilation and Execution**:
   - Express.js receives the HTTP requests and uses `body-parser` to parse the incoming request body.
   - `compilex` is used to compile and execute the code on the server for C++, Java, and C.
    - body-parser in a Node.js/Express application is to parse the incoming request bodies and make the parsed data available on the req.body object. When a client sends data to your server
    - HTTP POST request with form data or JSON payload, body-parser processes that data and attaches it to the request object (req) so that you can access it in your server-side code.

## Contributing

Contributions are welcome! If you have any ideas for improvement or new features, feel free to submit a pull request.

![ssjava](https://github.com/contributerMe/Icode-online-code-editor/assets/130450352/b491613b-a3f6-4413-8937-52df5127d24b)
![image](https://github.com/contributerMe/Icode-online-code-editor/assets/130450352/a21dfe48-12c9-403a-8c8e-784fa0e7b0e1)


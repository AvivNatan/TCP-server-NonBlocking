# Time Server

This project is a simple Time Server implemented in C++ using Winsock2. The server listens for incoming connections and handles various HTTP methods such as GET, POST, PUT, DELETE, HEAD, TRACE, and OPTIONS.

## Features

- Handles multiple client connections.
- Supports various HTTP methods.
- Non-blocking socket operations.
- Timeout handling for inactive connections.

## Prerequisites

- Visual Studio 2022
- Windows operating system
- Winsock2 library

## Getting Started

### Clone the Repository

git clone https://github.com/yourusername/timeserver.git cd timeserver

### Open the Project

1. Open Visual Studio 2022.
2. Go to `File` -> `Open` -> `Project/Solution`.
3. Navigate to the cloned repository and open the `TimeServer.sln` file.

### Build and Run

1. Build the project by clicking on `Build` -> `Build Solution`.
2. Run the project by clicking on `Debug` -> `Start Debugging`.

## Project Structure

- `WebServer/Server.cpp`: Main server implementation.
- `WebServer/Server.h`: Header file for server declarations.
- `WebServer/MethodImp.cpp`: Implementation of HTTP method handlers.
- `WebServer/MethodImp.h`: Header file for HTTP method handlers.

## Technologies Used

- **C++**: The project is written in C++, taking advantage of modern C++ features for better performance and readability.
- **Winsock2**: Used for network communication, providing a robust API for handling sockets and network operations.
- **HTTP Protocol**: The server supports various HTTP methods, making it versatile for different types of web requests.
- **Non-blocking I/O**: The server uses non-blocking sockets to handle multiple connections efficiently without blocking the main execution thread.
- **Timeout Management**: Implements timeout handling to close inactive connections, ensuring resources are not wasted on idle clients.

## Usage

The server listens on a specified port and handles incoming HTTP requests. It supports the following methods:

- `GET`: Retrieve data from the server.
- `POST`: Send data to the server.
- `PUT`: Update data on the server.
- `DELETE`: Delete data from the server.
- `HEAD`: Retrieve headers from the server.
- `TRACE`: Echo the received request.
- `OPTIONS`: Retrieve supported HTTP methods.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## Contact

For any questions or suggestions, please open an issue on GitHub.

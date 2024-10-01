# HTTP Web Server Implementation in C++

## Project Overview
This project is an implementation of a lightweight web server in C++ using the HTTP protocol. The server is designed to handle incoming HTTP requests, serve static files, and manage multiple client connections concurrently.

## Key Features

- **Socket Programming**: Utilized C++ socket APIs to establish a TCP connection on port 8080, enabling communication with clients.

- **Request Handling**: Implemented parsing of HTTP requests to identify the method, requested resource, and headers, ensuring proper interpretation of client intentions.

- **Static File Serving**: The server is capable of serving various static content types, including HTML, CSS, JavaScript, and image files, allowing clients to retrieve web resources seamlessly.

- **HTTP Response Generation**: Developed functionality to construct and send accurate HTTP responses, including status codes (e.g., 200 OK, 404 Not Found) and headers (Content-Type, Content-Length), ensuring compliance with the HTTP specification.

- **Multithreading**: Employed a multithreaded approach to handle multiple client connections simultaneously, significantly improving server responsiveness and performance.

- **Logging Mechanism**: Implemented logging features to track incoming requests and responses, aiding in debugging and monitoring server activity.

## Technologies Used

- **C++**: Core programming language for the server implementation.
- **POSIX Threads (pthreads)**: For managing concurrent client connections.
- **CMake**: For building the project and managing dependencies.

## Outcome
The implemented web server successfully accepts and processes multiple HTTP requests, serving static files while providing appropriate error handling and logging. This project demonstrates a strong understanding of networking concepts, the HTTP protocol, and multithreading in C++.

## How to Build and Run

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>

# HTTP Web Server Implementation in C++

## Project Overview
This project is an implementation of a lightweight web server in C++ using the HTTP protocol. The server is designed to handle incoming HTTP requests, serve static files, and manage multiple client connections concurrently through multiplexing.

## Key Features

- **Socket Programming**: Utilized C++ socket to establish a TCP connection on a port {specified en configue file}, enabling communication with clients.

- **Request Handling**: Implemented parsing of HTTP requests to identify the method, requested resource, and headers, ensuring proper interpretation of client intentions.

- **Static File Serving**: The server is capable of serving various static content types, including HTML, CSS, JavaScript, and image files, vedios, allowing clients to retrieve web resources seamlessly.

- **HTTP Response Generation**: Developed functionality to construct and send accurate HTTP responses, including status codes (e.g., 200 OK, 404 Not Found ...) and headers (Content-Type, Content-Length ...), ensuring compliance with the HTTP specification.

- **Multiplexing**: Employed multiplexing techniques to handle multiple client connections simultaneously, significantly improving server responsiveness and performance without the complexity of multithreading.

- **CGI Support**: Implemented Common Gateway Interface (CGI) capabilities to execute server-side scripts written in:
  - **PHP**: For dynamic content generation using PHP scripts.
  - **Python**: To allow execution of Python scripts for backend processing.
  - **Perl**: Enabling the execution of Perl scripts for server-side operations.

- **Session Management**: Added functionality to manage user sessions, allowing the server to track user activity and maintain state across multiple requests.

- **Cookie Handling**: Implemented support for HTTP cookies, enabling the server to set and read cookies in client requests for session tracking and personalization.

## Outcome
The implemented web server successfully accepts and processes multiple HTTP requests, serving static files while providing appropriate error handling and logging. This project demonstrates a strong understanding of networking concepts, the HTTP protocol, and multithreading in C++.

# Basic Rust WebServer

A simple web server implementation in Rust, created as a learning project to understand web server fundamentals and Rust programming concepts.

## Project Overview

This project implements a basic HTTP web server from scratch using Rust. It handles fundamental web server operations including:

- TCP connection handling
- HTTP request parsing
- Basic routing
- Static file serving
- Response generation

## Features

- Single-threaded request handling
- Support for GET requests
- Basic HTTP/1.1 protocol implementation
- Static file serving capability
- Custom 404 Not Found handling
- Request logging

## Prerequisites

- Rust (latest stable version)
- Cargo (Rust's package manager)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/rust-webserver.git
cd rust-webserver
```

2. Build the project:
```bash
cargo build
```

## Usage

1. Start the server:
```bash
cargo run
```

By default, the server will start on `localhost:8080`

2. Access the server:
- Open your web browser and navigate to `http://localhost:8080`
- Or use cURL: `curl http://localhost:8080`

## Project Structure

```
src/
├── main.rs          # Entry point and server initialization
├── server.rs        # Server implementation
├── http/
│   ├── request.rs   # HTTP request parsing
│   └── response.rs  # HTTP response generation
└── router.rs        # Request routing logic
```

## Learning Objectives

- Understanding TCP/IP networking in Rust
- HTTP protocol implementation
- Rust's ownership and borrowing system
- Error handling in Rust
- Project structure and organization
- Basic concurrency concepts

## Future Improvements

- [ ] Multi-threading support
- [ ] Configuration file support
- [ ] HTTP POST request handling
- [ ] Dynamic route handling
- [ ] Response compression
- [ ] HTTPS support
- [ ] WebSocket support

## Contributing

This is a learning project, but contributions and suggestions are welcome! Please feel free to:

1. Fork the repository
2. Create a feature branch
3. Submit a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Rust Programming Language Documentation
- [Rust Book](https://doc.rust-lang.org/book/)
- [HTTP/1.1 RFC](https://tools.ietf.org/html/rfc2616)

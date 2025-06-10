# Go Movie Server

A simple movie server built with Go. This project provides a RESTful API for managing a collection of movies.

## Features

- List all movies
- Add, update, and delete movies
- Search movies by title or genre
- JSON-based API

## Getting Started

### Prerequisites

- [Go](https://golang.org/dl/) 1.18 or higher

### Installation

```bash
git clone https://github.com/yourusername/go-movie-server.git
cd go-movie-server
go mod tidy
```

### Running the Server

```bash
go run main.go
```

The server will start on `http://localhost:8080`.

## API Endpoints

| Method | Endpoint         | Description           |
|--------|------------------|----------------------|
| GET    | `/movies`        | List all movies      |
| GET    | `/movies/{id}`   | Get movie by ID      |
| POST   | `/movies`        | Add a new movie      |
| PUT    | `/movies/{id}`   | Update a movie       |
| DELETE | `/movies/{id}`   | Delete a movie       |

## License

[MIT](LICENSE)
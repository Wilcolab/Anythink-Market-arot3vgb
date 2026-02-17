# Express Server Project

This is a simple Express server project that listens on port 8001. The server is set up to automatically reload using nodemon during development.

## Project Structure

```
express-server
├── src
│   └── server.js          # Entry point of the application
├── Dockerfile             # Dockerfile to build the server image
├── .dockerignore          # Files to ignore when building the Docker image
├── .gitignore             # Files to ignore in Git
├── package.json           # Project metadata and dependencies
├── yarn.lock              # Dependency version lock file
└── README.md              # Project documentation
```

## Getting Started

### Prerequisites

- Node.js and npm installed
- Yarn package manager installed

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/Wilcolab/Anythink-Market-arot3vgb.git
   cd Anythink-Market-arot3vgb/express-server
   ```

2. Install dependencies:
   ```
   yarn install
   ```

### Running the Server

To start the server with automatic reloading, use the following command:

```
yarn start
```

The server will be running on [http://localhost:8001](http://localhost:8001).

### Docker

To build and run the server using Docker, use the following commands:

1. Build the Docker image:
   ```
   docker build -t express-server .
   ```

2. Run the Docker container:
   ```
   docker run -p 8001:8001 express-server
   ```

### License

This project is licensed under the MIT License.
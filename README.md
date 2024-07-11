# FastTaskAPI

FastTaskAPI is a project built with FastAPI and ArangoDB, designed to manage tasks.

## Getting Started

### Prerequisites

Make sure you have the following installed on your machine:

- Docker
- Node.js (for Yarn)

### Installation

Clone the repository:

```bash
git clone https://github.com/hoangchuongit/fast-task-api
cd fasttaskapi
```

#### Install dependencies:

```bash
yarn install
```

### Running the Application

#### Development

To run the application in development mode:

```bash
yarn dev
```

This command will start the FastAPI server with auto-reload and connect to the development database specified in .env.

#### Production

To run the application in production mode:

```bash
yarn prod
```

This command will start the FastAPI server optimized for production environment.

### Stopping the Application

To stop the running Docker containers:

```bash
yarn down
```

### Code Formatting and Linting

```bash
yarn lint
```

To format your Python code using Black:

```bash
yarn format
```

### Configuration

Make sure to configure your environment variables in `.env` file. Here is an example configuration:

```dotenv
# Environment variables for FastTaskAPI

# Database settings
DB_HOST=db
DB_PORT=8529
DB_USER=root
DB_PASSWORD=rootpassword
DB_NAME=fasttask
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

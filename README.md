
---

# PathoGin

**PathoGin** is a tool designed for analyzing and identifying pathogenic sequences from genetic data. It streamlines the process of pathogen detection by providing an efficient workflow for bioinformatics research, making it easier to analyze, test, and deploy the application across different environments. The tool is geared towards researchers and developers looking for a robust, automated solution to handle pathogen-related genetic data processing and analysis.

## Getting Started

Follow these instructions to get a local copy of the project up and running for development and testing purposes. Check the deployment section for notes on how to deploy the project in a production environment.

### Prerequisites

Ensure you have the following installed:
- Docker
- GNU Make

## MakeFile Commands

Use the following commands to manage the application:

- **Run build and tests**  
   Compiles the project and runs the test suite:
   ```bash
   make all
   ```

- **Build the application**  
   Creates a build of the application:
   ```bash
   make build
   ```

- **Run the application**  
   Executes the application locally:
   ```bash
   make run
   ```

- **Create DB container**  
   Spins up a Docker container with the database:
   ```bash
   make docker-run
   ```

- **Shutdown DB container**  
   Stops and removes the running Docker container for the database:
   ```bash
   make docker-down
   ```

- **Run DB Integration Tests**  
   Executes database integration tests:
   ```bash
   make itest
   ```

- **Live reload the application**  
   Watches for file changes and reloads the application automatically:
   ```bash
   make watch
   ```

- **Run the test suite**  
   Runs all tests in the project:
   ```bash
   make test
   ```

- **Clean up**  
   Removes the binary from the previous build:
   ```bash
   make clean
   ```

---


# MyApp-DevOps-Assignment

This repository contains a Docker Compose configuration to deploy a multi-service application consisting of a Go application, a Next.js application, a WordPress application, and a MySQL database.

Apps GitHub Repo - 
- Go-app repo: (https://github.com/itsbharatsaini/go-app)
- Next.js-app repo: (https://github.com/itsbharatsaini/nextjs-app)
- WordPress-app repo: (https://github.com/itsbharatsaini/wordpress-app)

## Prerequisites

Before you begin, make sure you have Docker and Docker Compose installed on your system.

- [Install Docker](https://docs.docker.com/get-docker/)
- [Install Docker Compose](https://docs.docker.com/compose/install/)

## Usage

1. Clone this repository to your local machine:

    ```bash
    https://github.com/itsbharatsaini/MyApp-DevOps-Assignment.git
    ```

2. Navigate to the cloned repository directory:

    ```bash
    cd MyApp-DevOps-Assignment
    ```

3. Customize the Docker Compose file (`docker-compose.yml`) if necessary. You can adjust ports, passwords, or other configurations according to your requirements.

4. Run the following command to start all the services defined in the Docker Compose file:

    ```bash
    docker-compose up -d
    ```

    This command will start all the services in detached mode (in the background).

5. Once the containers are up and running, you can access the applications using the following URLs:

    - Go application: (http://localhost:8080)
    - Next.js application: (http://localhost:3000)
    - WordPress application: (http://localhost:8800)

6. To stop all the containers, run:

    ```bash
    docker-compose down
    ```

    This will stop and remove all the containers.

## Configuration

- Each service in the Docker Compose file can be configured with environment variables or volume mounts.

## Notes

- Ensure that you must update passwords for MySQL for security reasons.

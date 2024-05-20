# LEMP Wordpress Setup

This repository contains a Dockerized setup for running WordPress with a LEMP (Linux, Nginx, MySQL, PHP) stack.

## Prerequisites

Make sure you have Docker and Docker Compose installed on your system.

## Setup Instructions

1. Clone this repository:

    ```bash
    git clone <repo-url>
    ```

2. Navigate to the cloned repository:

    ```bash
    cd lemp-wordpress
    ```

3. Build the PHP service using Docker Compose:

    ```bash
    docker-compose build php
    ```

4. Start the Docker containers in detached mode:

    ```bash
    docker-compose up -d
    ```

5. Access WordPress in your browser:

    Visit [http://localhost:8001/](http://localhost:8001/) to begin the WordPress installation process.

Follow the on-screen instructions to complete the WordPress setup.


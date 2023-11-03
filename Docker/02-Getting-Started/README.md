# Getting Started with Docker

Welcome to the "Getting Started with Docker" tutorial. In this tutorial, you'll learn the basics of Docker and how to get started with containerization.

## Installing Docker

To begin your Docker journey, you need to install Docker on your computer. Follow these steps to get Docker up and running:

1. Visit the [Docker website](https://docs.docker.com/get-docker/) and download Docker for your operating system.

2. Follow the installation instructions for your platform.

3. Verify the installation by running the following command in your terminal:

   ```bash
   docker --version
   ```

You should see the Docker version information if the installation was successful.

## Running Your First Container

Now that Docker is installed, let's run your first container. We'll use the official "hello-world" container to get started.

1. Open your terminal or command prompt.

2. Run the following command to pull and run the "hello-world" container:

   ```bash
   docker run hello-world
   ```

3. Docker will download the "hello-world" image and execute it.

4. You'll see a message indicating that your installation appears to be working correctly.

## Basic Docker Commands

Docker provides a wide range of commands for managing containers and images. Here are some basic commands to get you started:

- `docker run`: Run a container from an image.
- `docker ps`: List running containers.
- `docker ps -a`: List all containers (including stopped ones).
- `docker images`: List available images.
- `docker stop <container_id>`: Stop a running container.
- `docker rm <container_id>`: Remove a container.

That's it for your introduction to Docker! You're now ready to explore more advanced Docker features in the upcoming sections.

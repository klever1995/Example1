# Example1: Simple Python Flask App in Docker

A simple Python program that greets the user, dockerized for easy execution in any environment.

## Description

This is a basic Python program using Flask. The program displays a welcome message on a webpage when accessed at the root (`/`) route in a browser.

## Technologies Used

- Python 3.9
- Flask
- Docker

## Prerequisites

To run this project, you need to have Docker installed on your machine. If you don't have it, you can download it from [here](https://www.docker.com/products/docker-desktop).

## Instructions to Run the Project

1. **Clone this repository:**

   If you haven't cloned the repository yet, you can do so with the following command:

   ```bash
   git clone https://github.com/klever1995/Example1.git

2. **Pull the Docker image:** 
   Before running the container, pull the Docker image with the following command:

   ```bash
   docker pull ksrobalino/example_python:v1

3. **Run the Docker container:** 
   After pulling the image, run the container using this command:

   ```bash
   docker run -d -p 5000:5000 --name mi_contenedor ksrobalino/example_python:v1

4. **Access the application:** 
   Once the container is running, you can access the application by navigating to the following URL in your web browser:
   http://localhost:5000
   
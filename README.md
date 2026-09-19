# Greeter

A simple Python web application that displays a greeting message. The application uses Python's built-in `http.server` and is containerized using Docker.

## Run with Docker

### Build the image

docker build -t greeter:1.1

### Run the container

docker run -d --name greeter-container -p 8080:8080 greeter:1.1

# simple-dockerised-flask-app
A simple Dockerised python flask app

To run the containerised web app on your machine, first make sure Docker desktop is running and run the following commands from your CLI:

$ sudo docker build -t myapp:latest .

$ sudo docker run -p 9090:90 -t myapp:latest

Run the following command to see if the container is up and running:

$ sudo docker ps

This should run a Docker container and map port 9090 of your machine to port 90 of the docker container. Go to "localhost:9090" from your browser to access the web app.

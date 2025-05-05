# Docker

## 0. Create Your First Docker Image
- To create a Docker image, you will need to utilize a Dockerfile. Create a Dockerfile that:
	- Is based on the latest ubuntu
	- Update APT using apt-get update
	- Upgrade currently installed software through APT using apt-get upgrade -y
	- Once built, you can run the Docker image in a container and it will echo “Hello, World!” on the terminal.

## 1. Back-end
- For this task, start by making a copy of your `task0` directory and name it `task1`. Next, we want to change the `Dockerfile` to install Python3, pip3, and Flask. You may not have used Flask, yet, but not to worry; for this project, we will give you all of the Flask code you need to get started. We’ll validate that all have been installed correctly by running a Flask server with one endpoint that when called returns “Hello, World!”

## 2. Front-end
- For this task, start by making a copy of your `task1` directory and name it `task2`. We have created a very simple API server with one route that returns “Hello, World!” and now we want to create a web page to view content from our API server in the context of a more full front-end. Before creating our front end, let’s reorganize this project a bit in our `task2` directory.
	- Create a new directory named `back-end` inside of your `task2` directory.
	- Move all of the files currently in task2 inside of the new back-end directory.

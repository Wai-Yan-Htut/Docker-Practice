Solution for Basic Dockerfile project form roadmap.sh [https://roadmap.sh/projects/basic-dockerfile]

How to run the project?

First, simply clone the git repo. You will find the docker file in the directory.

Then, run this command inside the directory

docker build -t IMAGE-NAME .

This will build an image with your choice of name from the docker file.

Then, simply run this command to run the conatiner and output the text to the console.

docker run -d --name CONTAINER-NAME IMAGE-NAME

The container will run and the output "Hello, Captain!" will be outputted to the console and the docker container will exit. It is done. You can delete everything now if you wish to.

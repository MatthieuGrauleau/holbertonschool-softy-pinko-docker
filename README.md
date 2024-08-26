0. Create Your First Docker Image
mandatory
To create a Docker image, you will need to utilize a Dockerfile. Create a Dockerfile that:

Is based on the latest ubuntu
Update APT using apt-get update
Upgrade currently installed software through APT using apt-get upgrade -y
Once built, you can run the Docker image in a container and it will echo “Hello, World!” on the terminal.
Example (your output may look different depending on your local environment and whether or not you have cached data):
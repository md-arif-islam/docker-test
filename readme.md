# Docker Image Management

This repository contains the Dockerfile and other configuration files required to build a Docker image for running the application.

### Building the Docker Image

To build the Docker image, you will first need to install Docker on your local machine. Once you have Docker installed, you can use the following command to build the image:

```
docker build -t <image-name> .
```

This command will build the Docker image using the Dockerfile in the current directory and tag it with the name **`<image-name>`**.

### Viewing Docker Images

To view the Docker images that are currently available on your local machine, you can use the following command:

```
docker images
```

This will display a list of all the Docker images that are currently available on your machine, including their names, tags, and sizes.

### Tagging Docker Images

Once you have built a Docker image, you may want to tag it with a specific name or version number. To do this, you can use the following command:

```
docker tag <image-name> <user-name>/<file-name>:<tag-name>
```

This will create a new tag for the specified Docker image, using the format **`<user-name>/<file-name>:<tag-name>.`** You can then push this tagged image to a Docker registry or use it to run containers on your local machine.

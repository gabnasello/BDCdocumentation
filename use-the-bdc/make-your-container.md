# Make your own container

### Start from an existing Docker image

Start from an existing Docker container on top of which you want to install new applications or specific Python/R packages and clone the directory to build the image from GitHub.

For example, build your image starting from [`slicer-env`](https://github.com/gabnasello/slicer-env):

`git clone https://github.com/gabnasello/slicer-env.git`

### Building a new Docker Container Image

Learn the basics from [this online guide](https://chtc.cs.wisc.edu/uw-research-computing/docker-build).&#x20;

Once you modify the Dockerfile, you can run:

`bash build.sh`

To build the new image.

### Exploring a Docker Container on Your Computer

Learn the basics of the `docker compose` command from the [Docker documentation](https://docs.docker.com/compose/gettingstarted/).&#x20;

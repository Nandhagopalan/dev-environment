# Dev-Environment
This is for the local container based development setup


Follow the below steps for faster development process

1. Get base image and install core packages and save the image
2. Build on top of base image for project specific dependencies.


### Docker Command to get started

`docker run --net=host -e DISPLAY=$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix -v /home/nandhu/Downloads/deploy_stable_difusion:/home/ -it nandhu:1.0 bash`

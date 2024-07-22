FROM node:14-alpine

# All commands will be working right here, directly in this WORKDIR
WORKDIR /app

# To avoid adding a lot of npm, to execute just something like this:
# docker run -it -v /home/user/l_docker_compose/utility-containers:/app node-util npm init
ENTRYPOINT [ "npm" ]
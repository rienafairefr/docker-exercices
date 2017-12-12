# base image: last debian release
FROM debian:jessie

# install the latest upgrades
RUN apt-get update && apt-get -y dist-upgrade

# TODO install nginx
# ...

RUN apt-get update && apt-get -y install nginx

# TODO set the default container command command (CMD) to run the nginx daemon
# ...

CMD ["nginx", "-g", "daemon off;"]



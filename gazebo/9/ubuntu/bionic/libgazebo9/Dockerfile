# This is an auto generated Dockerfile for gazebo:libgazebo9
# generated from docker_images/create_gzclient_image.Dockerfile.em
FROM gazebo:gzserver9-bionic
# install gazebo packages
RUN apt-get update && apt-get install -q -y \
    libgazebo9-dev=9.4.1-1* \
    && rm -rf /var/lib/apt/lists/*

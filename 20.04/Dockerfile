FROM ubuntu:20.04

WORKDIR /app

# Update repositories and install packages and
RUN apt-get update && apt install -y python3 python3-pip git-core curl jq
RUN pip3 install gigalixir --ignore-installed six

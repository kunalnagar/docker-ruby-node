FROM ruby:2.7-slim

LABEL maintainer="Kunal Nagar <knlnagar@gmail.com>"

SHELL ["/bin/bash", "-o", "pipefail", "-c"]

RUN apt-get update && apt-get install -y curl

RUN curl -sL https://deb.nodesource.com/setup_12.x | bash -

RUN apt-get install -y nodejs \
	&& rm -rf /var/lib/apt/lists/*

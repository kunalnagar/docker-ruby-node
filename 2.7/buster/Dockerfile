FROM ruby:2.7

LABEL maintainer="Kunal Nagar <knlnagar@gmail.com>"

SHELL ["/bin/bash", "-o", "pipefail", "-c"]

RUN curl -sL https://deb.nodesource.com/setup_12.x | bash -

RUN apt-get update -qq && apt-get install -qq --no-install-recommends \
	apt-utils nodejs \
	&& rm -rf /var/lib/apt/lists/*

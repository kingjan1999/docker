FROM gradle:jdk

#MAINTAINER Jan Beckmann <jan@jbeckmann.info>
LABEL Description="gradle:jdk image including openjfx" Maintainer="jan@jbeckmann.info"

USER root
RUN apt-get update && apt-get install -y --no-install-recommends openjfx && rm -rf /var/lib/apt/lists/*

USER gradle

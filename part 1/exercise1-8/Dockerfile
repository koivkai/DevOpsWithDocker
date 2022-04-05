FROM ubuntu:20.04

WORKDIR /usr/src/app

RUN apt-get update; apt-get -y install curl

COPY curler-script.sh .

RUN chmod +x curler-script.sh

CMD sh curler-script.sh
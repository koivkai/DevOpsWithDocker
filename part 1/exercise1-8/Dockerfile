FROM ubuntu:20.04

WORKDIR /usr/src/app

RUN apt-get update; apt-get install curl

COPY curler-script.sh .

RUN chmod +x curler-script.sh

CMD ./curler-script.sh
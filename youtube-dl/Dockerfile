FROM ubuntu:latest
MAINTAINER kjbweb <mail@kjbweb.net>

RUN apt-get update && \
    apt-get install ffmpeg curl python rename -y && \
    curl -L https://yt-dl.org/downloads/latest/youtube-dl -o /usr/local/bin/youtube-dl && \
    chmod a+rx /usr/local/bin/youtube-dl

CMD [ "/usr/local/bin/youtube-dl" ]

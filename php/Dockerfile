
FROM arziel/php:latest

RUN apt-get update -qq && apt-get install -y curl python ffmpeg

RUN curl -L https://yt-dl.org/downloads/latest/youtube-dl -o /usr/local/bin/youtube-dl

RUN chmod a+rx /usr/local/bin/youtube-dl

WORKDIR /var/docker

FROM node:5

MAINTAINER cv

EXPOSE 8125/udp
EXPOSE 8126

RUN git clone https://github.com/etsy/statsd.git /opt/statsd && cd /opt/statsd && npm install git+https://github.com/gillesdemey/statsd-influxdb-backend.git
ADD config.js /opt/statsd/config.js
WORKDIR /opt/statsd
CMD ["node","stats.js","config.js"]
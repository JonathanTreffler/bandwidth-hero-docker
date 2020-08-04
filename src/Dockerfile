FROM node:8

EXPOSE 8000

RUN mkdir /app/

RUN cd / && git clone https://github.com/ayastreb/bandwidth-hero-proxy /app/

RUN cd /app && npm install

ENTRYPOINT ["node", "/app/server.js"]

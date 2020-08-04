FROM node:8

EXPOSE 8000

RUN git clone https://github.com/ayastreb/bandwidth-hero-proxy

RUN cd bandwidth-hero-proxy && npm install

RUN mkdir /app/

COPY bandwidth-hero-proxy/ /app/

ENTRYPOINT ["node", "/app/server.js"]

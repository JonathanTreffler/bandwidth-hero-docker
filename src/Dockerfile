FROM node:14
EXPOSE 8000

RUN git clone https://github.com/ayastreb/bandwidth-hero-proxy

WORKDIR bandwidth-hero-proxy

RUN npm install

WORKDIR ..

COPY bandwidth-hero-proxy /app/

ENTRYPOINT ["node", "/app/server.js"]

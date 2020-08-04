FROM node:8
EXPOSE 8000

RUN git clone https://github.com/ayastreb/bandwidth-hero-proxy

RUN ls -la

WORKDIR bandwidth-hero-proxy

RUN npm install

WORKDIR ..

RUN ls -la

COPY bandwidth-hero-proxy /app/

ENTRYPOINT ["node", "/app/server.js"]

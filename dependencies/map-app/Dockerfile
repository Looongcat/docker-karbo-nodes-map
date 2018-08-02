FROM node:8

RUN npm install axios@0.18.0 cacheman-memory@1.1.0 express@4.16.3 yargs@12.0.1
WORKDIR /usr/src/app
EXPOSE 8081/tcp

ENTRYPOINT ["node", "app.js"]
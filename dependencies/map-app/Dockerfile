FROM node:10

WORKDIR /usr/src/app

COPY ./data/map-app/ ./

#RUN npm config set package-lock false

RUN npm i

EXPOSE 8081/tcp

ENTRYPOINT ["node", "app.js"]

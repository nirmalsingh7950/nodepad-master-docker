FROM node:7
WORKDIR /nodepad/app

COPY package*.json .

RUN npm install

COPY . .

EXPOSE 8080

CMD [ "node", "app.js" ]




FROM node:20.9.0
LABEL author="Joao Victor"
WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8080

CMD [ "node", "server.js" ]
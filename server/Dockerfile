FROM node:18.17.0

WORKDIR /usr/src/server

COPY package*.json ./

RUN npm install 

COPY . .

EXPOSE 3000

CMD ["node", "server.js"]
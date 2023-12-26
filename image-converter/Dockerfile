FROM node:18.17.0

WORKDIR /imageconverter

COPY package*.json ./

RUN npm install 

COPY . .

CMD ["node", "imageconverter.js"]
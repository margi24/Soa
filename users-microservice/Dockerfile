FROM node:12-alpine
WORKDIR /usr/src/app
COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8090

CMD ["node", "index.js"]
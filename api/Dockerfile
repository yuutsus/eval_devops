FROM node:13.8.0-alpine

RUN mkdir -p /usr/src/app

WORKDIR /usr/src/app

ENV PORT 3000

EXPOSE 8080

COPY package*.json ./

RUN npm install

COPY . .

CMD [ "npm", "run", "dev" ]
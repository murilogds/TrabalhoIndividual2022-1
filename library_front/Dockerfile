FROM node:latest

COPY package*.json app/

WORKDIR /app

RUN npm install

COPY . .

EXPOSE 3000
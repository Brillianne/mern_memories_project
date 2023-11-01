FROM node:18.17.1-alpine

RUN mkdir -p app

WORKDIR /app

COPY . /app 

RUN npm install

CMD [ "npm", "start" ]
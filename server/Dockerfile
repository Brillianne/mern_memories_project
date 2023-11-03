FROM node:18.17.1-alpine
WORKDIR /usr/app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 5000
RUN npm run
CMD ["node", "index.js"]

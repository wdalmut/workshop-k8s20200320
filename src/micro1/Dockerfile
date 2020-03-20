FROM node:12-alpine

WORKDIR /app

COPY package.json package.json

RUN npm install

COPY src src

CMD ["node", "src/index.js"]

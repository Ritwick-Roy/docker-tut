FROM node:18-alpine

RUN npm i -g nodemon

WORKDIR /app

COPY package.json .

RUN npm i

COPY . .

EXPOSE 4000

CMD ["npm","run","dev"]
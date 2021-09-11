FROM node:alpine

LABEL marcelo-gonçalves="tchelojg@gmail.com"

WORKDIR /app

COPY package.json ./

RUN npm install

COPY ./ ./

CMD ["npm", "start"]
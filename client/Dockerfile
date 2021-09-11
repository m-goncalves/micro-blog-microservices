FROM node:alpine
 
LABEL marcelo-gonçalves="tchelojg@gmail.com"

ENV CI=true
 
WORKDIR /app

COPY package.json ./

RUN npm install

COPY ./ ./
 
CMD ["npm", "start"]
FROM node:16.14-alpine

WORKDIR /backend

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 40001

CMD ["npm", "run", "dev"]
FROM node:10.15.0

ENV REFRESHED_AT 2020-04-04

WORKDIR /api

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3030

CMD ["npm", "run", "dev"]
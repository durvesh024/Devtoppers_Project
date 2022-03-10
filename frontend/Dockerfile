FROM node:17.6.0-alpine3.14
WORKDIR /app
COPY package.json .
RUN npm install
COPY . .
EXPOSE 3000
CMD [ "npm","start" ]
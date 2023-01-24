FROM node:16-alpine
LABEL maintainer="mganalistati@gmail.com"
WORKDIR /conversao
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
ENTRYPOINT ["node", "server.js"]

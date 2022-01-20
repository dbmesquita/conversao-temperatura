FROM node:14.18.3-buster-slim
WORKDIR /app
COPY ./package*.json ./
RUN npm install
COPY . .
EXPOSE 800
ENTRYPOINT ["node","server.js"]

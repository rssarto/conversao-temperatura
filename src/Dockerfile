FROM node:18.13-alpine
WORKDIR /app
COPY ./package*.json /app/
RUN npm install
COPY . .
EXPOSE 8080
ENTRYPOINT [ "node", "server.js" ]

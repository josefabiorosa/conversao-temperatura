FROM node:20-alpine3.21
WORKDIR /app
COPY package*.json .
RUN npm install
COPY . .
EXPOSE 8080
ENTRYPOINT [ "node","server.js" ]
LABEL CONTATO="JOSE FABIO ROSA"
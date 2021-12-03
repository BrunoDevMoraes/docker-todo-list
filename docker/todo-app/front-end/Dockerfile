FROM node:14-alpine
EXPOSE 3000
WORKDIR /app
ENTRYPOINT npm start

ADD node_modules.tar.gz .

COPY package*.json ./
RUN npm install
COPY . .
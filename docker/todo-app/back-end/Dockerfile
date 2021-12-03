FROM node:14-alpine
EXPOSE 3001
WORKDIR /app
ENTRYPOINT npm start

ADD ./node_modules.tar.gz .

COPY package*.json ./
RUN npm install
COPY . .
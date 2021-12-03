FROM mjgargani/puppeteer:trybe1.0
EXPOSE 3000
WORKDIR /app
ENTRYPOINT npm test

ADD node_modules.tar.gz .

COPY package*.json ./
RUN npm install
COPY . .
FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app

ADD node_modules.tar.gz .

COPY . .

RUN npm install

EXPOSE 3001

CMD ["npm", "test"]
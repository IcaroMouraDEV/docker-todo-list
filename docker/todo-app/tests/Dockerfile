FROM mjgargani/puppeteer:trybe1.0

WORKDIR /usr/src/app

ADD ./node_modules.tar.gz ./

COPY package*.json .

RUN npm install

COPY . .

CMD ["npm", "test"]


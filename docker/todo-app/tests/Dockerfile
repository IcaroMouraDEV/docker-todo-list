FROM mjgargani/puppeteer:trybe1.0

WORKDIR /usr/src/app

ADD ./node_modules.tar.gz /usr/src/app

COPY package*.json /usr/src/app

RUN npm install

COPY . /usr/src/app

CMD ["npm", "test"]


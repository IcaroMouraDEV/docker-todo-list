FROM mjgargani/puppeteer:trybe1.0

WORKDIR /docker-todo-list

ADD ./node_modules.tar.gz .

COPY . .

CMD ["npm", "test"]


FROM node:14

WORKDIR /docker-todo-list

ADD ./node_modules.tar.gz .

COPY . .

EXPOSE 3001

CMD ["npm", "start"]
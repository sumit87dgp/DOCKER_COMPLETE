FROM node

WORKDIR /app

COPY . /app

RUN npm config set registry http://registry.npmjs.org/

RUN npm install

EXPOSE 80

CMD ["node", "server.js" ]

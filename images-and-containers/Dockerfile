FROM node

WORKDIR /src

COPY package*.json /app

RUN npm install

COPY . .

EXPOSE 3000

CMD [ "node", "app.js" ]
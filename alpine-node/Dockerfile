FROM mhart/alpine-node:10.5.0

WORKDIR /app

COPY package*.json ./

RUN yarn install

COPY . . 

CMD yarn start
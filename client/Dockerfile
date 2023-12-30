FROM node:18-alpine

WORKDIR /client/src

COPY package.json yarn.lock ./

RUN yarn install

COPY . .

EXPOSE 3000
CMD ["yarn", "start"]

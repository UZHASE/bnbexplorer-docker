FROM node:14-alpine

ADD bnbexplorer-frontend/package.json /bnbexplorer-frontend/package.json

WORKDIR /bnbexplorer-frontend

RUN yarn install

CMD ["yarn", "start"]
FROM node:8.6.0-alpine
MAINTAINER Chuka Ofili <ofili@microsmart.tk>

WORKDIR /www

RUN yarn global add serve
ADD ./package.json ./yarn.lock /www/
RUN yarn install

ADD ./ /www

RUN yarn build

CMD ["yarn", "start:prod"]

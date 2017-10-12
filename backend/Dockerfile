FROM node:8.6.0-alpine
LABEL maintainer="Chuka Ofili <ofili@microsmart.tk>"

WORKDIR /www

ADD ./package.json ./yarn.lock /www/
RUN yarn install \
	&& yarn cache clean;

ADD ./ /www

CMD ["yarn", "start"]

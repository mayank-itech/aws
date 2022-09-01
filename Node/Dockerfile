FROM node:12.4.0-alpine as debug

WORKDIR /usr/src/app

COPY ./package.json /usr/src/app/package.json
RUN npm install
EXPOSE 8080
COPY ./ /usr/src/app
CMD node .
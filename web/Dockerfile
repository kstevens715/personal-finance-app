FROM node:alpine

RUN mkdir -p /usr/src/web
WORKDIR /usr/src/web

COPY package.json /usr/src/web/
RUN npm install

COPY . /usr/src/web

EXPOSE 3001
CMD [ "npm", "start" ]

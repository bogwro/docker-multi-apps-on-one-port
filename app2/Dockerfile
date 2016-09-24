FROM node:6.6

RUN mkdir /app

COPY package.json /app

WORKDIR /app

RUN set -x \
        && npm install

COPY . /app

CMD ["npm", "start"]

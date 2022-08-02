FROM node:14

WORKDIR /usr/app

ADD ./node_modules.tar.gz ./node_modules

COPY . .

RUN ["npm", "install"]

EXPOSE 3001

CMD ["npm", "start"]
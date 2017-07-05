FROM node:alpine

WORKDIR /

ADD package.json /package.json
RUN npm install

ADD . /

CMD /bin/hubot --adapter slack

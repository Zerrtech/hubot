FROM node:alpine

WORKDIR /

ADD yarn.lock /yarn.lock
RUN yarn
RUN npm install

ADD . /

CMD /bin/hubot --adapter slack

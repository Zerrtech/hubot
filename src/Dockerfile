FROM node:alpine

ADD yarn.lock /yarn.lock
RUN yarn install

ADD . /

CMD /bin/hubot --adapter slack

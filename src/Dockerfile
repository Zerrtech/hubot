FROM node:alpine

WORKDIR /

ADD yarn.lock /yarn.lock
RUN yarn

ADD . /

CMD /bin/hubot --adapter slack

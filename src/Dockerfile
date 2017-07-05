FROM node:alpine

WORKDIR /

ADD yarn.lock /yarn.lock
ADD package.json /package.json
RUN yarn
RUN npm install

ADD . /

CMD /bin/hubot --adapter slack

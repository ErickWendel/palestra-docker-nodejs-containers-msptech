FROM node:10-alpine

LABEL autor="@erickwendel_"

ADD . src/

WORKDIR /src

RUN npm i -g typescript

RUN npm i 

RUN npm run build 

CMD npm start
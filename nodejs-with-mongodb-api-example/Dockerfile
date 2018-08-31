FROM node:10-alpine

LABEL autor="@erickwendel_"

ADD . src/

WORKDIR /src


RUN npm i -g typescript nodemon --production --silent

RUN npm i --production --silent

RUN npm run build 

# CMD npm start

## DEVELOPMENT EXAMPLE

CMD npm run dev
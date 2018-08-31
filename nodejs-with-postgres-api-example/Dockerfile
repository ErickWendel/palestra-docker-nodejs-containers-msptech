FROM node:8-alpine

ADD . src/

WORKDIR /src

RUN npm i -g typescript nodemon

RUN npm i 

RUN npm run build 

##DEVELOPMENT
CMD npm run dev
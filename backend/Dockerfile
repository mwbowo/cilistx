FROM node:alpine

WORKDIR /app

COPY .  /app

RUN apk update && apk add nano -f

RUN npm install

EXPOSE 5000

CMD ["npm","start"]
FROM node:alpine

COPY . /app

WORKDIR /app

RUN apk update && apk add nano -f

RUN cp .env.example .env

RUN npm install

EXPOSE 3000

CMD ["npm","start"]

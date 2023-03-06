FROM node:lts-gallium

COPY . /app

WORKDIR /app

RUN apt update && apt install nano -y

RUN npm install

EXPOSE 3000

CMD ["npm","start"]
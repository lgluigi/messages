FROM node:latest
EXPOSE 3000
ENV NODE_VERSION 16

COPY . /server
WORKDIR /server

RUN npm install --force

CMD ["npm","run","dev"]
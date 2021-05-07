FROM node:slim

RUN mkdir task
WORKDIR /task
COPY server.js .
RUN npm install express
EXPOSE 3000
CMD ["node", "server.js"]

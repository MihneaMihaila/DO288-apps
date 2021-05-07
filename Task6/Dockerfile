FROM node:slim
RUN mkdir task
WORKDIR /task
EXPOSE 3000
COPY ./server.js /task
RUN npm install express
CMD ["node", "./server.js"]

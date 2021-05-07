
FROM node:slim
WORKDIR /home
EXPOSE 3000
COPY ./server.js /home
RUN npm install express
CMD ["node", "./server.js"]

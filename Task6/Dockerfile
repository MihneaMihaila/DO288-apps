
FROM node:slim
WORKDIR /home
EXPOSE 3000
COPY ./Server.js /home
RUN npm install express
RUN npm install mysql
CMD ["node", "./Server.js"]

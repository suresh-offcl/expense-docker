FROM node:20
EXPOSE 8080
ENV db_host="mysql"
RUN mkdir /opt/server
WORKDIR /opt/server
COPY package.json .
COPY *.js .
RUN npm install
CMD [ "node","index.js" ] 
    #["npm", "start"]


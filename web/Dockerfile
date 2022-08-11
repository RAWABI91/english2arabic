FROM node:10-alpine
WORKDIR /var/www
LABEL author="Rawanbi Mohammed"
RUN npm install
COPY . .
EXPOSE 3000
VOLUME [ "/var/www" ]
CMD [ "node", "index.js" ]

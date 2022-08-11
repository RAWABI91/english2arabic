FROM node:10-alpine
LABEL author="Rawanbi Mohammed"
WORKDIR /var/www
COPY . .
RUN npm install
VOLUME [ "/var/www" ]
EXPOSE 3001
CMD [ "node", "index.js" ]
FROM node:12.18.3-alpine

LABEL author="blanccobb <blanccobb@gmail.com>"

RUN yarn global add pm2 n

WORKDIR /var/www/html

VOLUME [ "/var/www/html"]

EXPOSE 9000

CMD [ "pm2", "monit"]
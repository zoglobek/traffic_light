FROM node:20-alpine

WORKDIR /app

COPY package.json /app/.
COPY app.js /app/.
COPY index.pug /app/views/
COPY favicon.ico /app/views/

RUN npm install

EXPOSE 80

CMD ["node", "app.js"]
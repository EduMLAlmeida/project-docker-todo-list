FROM node:14-alpine

WORKDIR /front-end-app

COPY . .

RUN npm install

EXPOSE 3000

ENV REACT_APP_API_HOST=todobackend

ENV REACT_APP_API_PORT=3001

CMD ["npm", "start"]

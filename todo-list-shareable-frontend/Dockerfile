FROM node:18-alpine

WORKDIR /app/nestjs-backend

COPY ./vue-app/package*.json ./

RUN npm install

COPY todo-list-shareable-frontend .

EXPOSE 3000

CMD ["npm", "run", "dev"]

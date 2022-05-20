FROM node:18-alpine

WORKDIR /app/nestjs

COPY ./package*.json ./

RUN npm install

WORKDIR /app/nestjs-backend

COPY ./package*.json ./

RUN npm install

COPY todo-list-shareable-easv-backend .

EXPOSE 3000

CMD ["npm", "run", "dev"]

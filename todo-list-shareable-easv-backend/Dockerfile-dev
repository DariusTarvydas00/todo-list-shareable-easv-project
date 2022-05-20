FROM node:18-alpine

WORKDIR /app/nestjs-backend

COPY ./nest-app/package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "run", "dev"]

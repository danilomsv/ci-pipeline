FROM node:18-alpine

WORKDIR /app

COPY src/package*.json ./

RUN npm install

COPY src/ .

EXPOSE 5000

CMD ["npm", "start"]

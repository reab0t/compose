FROM node:16-alpine

WORKDIR /app

COPY src/package*.json ./
RUN npm install

COPY src/ .

EXPOSE 3000

CMD ["node", "app.js"] 
# Use official Node.js LTS image
FROM node:20-alpine

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

VOLUME ["/app/uploads"]

EXPOSE 3000

CMD ["node", "index.js"] 
FROM node:14.16.1-alpine3.13
# Create app directory
WORKDIR /app

# Install app dependencies
COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8080

CMD ["node", "app.js"]
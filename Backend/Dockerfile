#Base Image
FROM node:18-alpine

#Working Directory
WORKDIR /app

#installing packages
COPY package*.json ./
RUN npm install

#copying code
COPY . .
COPY .env .env

#port
EXPOSE 3000

#run
CMD ["node","index.js"]

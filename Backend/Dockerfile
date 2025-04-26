#Base Image
FROM node:18-alpine

#Working Directory
WORKDIR /app

#installing packages
COPY package*.json ./
Run npm install

#copying code
COPY . .

#run
CMD ["node","index.js"]

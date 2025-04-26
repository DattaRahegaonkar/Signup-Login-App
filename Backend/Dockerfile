#Base Image
FROM node:18-alpine

#Working Directory
WORKDIR /app

#installing packages
COPY package*.json ./
Run npm install

#copying code
COPY . .

#port
EXPOSE 3000

#run
CMD ["node","index.js"]

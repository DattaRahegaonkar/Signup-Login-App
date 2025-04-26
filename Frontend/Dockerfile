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
EXPOSE 5000

#run
CMD ["npm","run","dev","--host","--port","5000"]

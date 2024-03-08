# Use an official Node.js runtime as a parent image
FROM node:20-alpine3.18

WORKDIR /opt/app
COPY package.json .
COPY package-lock.json .
RUN npm install
COPY . .
EXPOSE 3000

# Define the command to run your app
CMD ["npm", "start"]

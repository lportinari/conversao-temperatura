FROM node:16.15.0
WORKDIR /app
# Copy packages to npm install
COPY ./package*.json ./
RUN npm install
# Copy all 
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]

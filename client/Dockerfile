FROM node:18-alpine
WORKDIR /app
COPY package*.json /app
RUN npm install 
RUN npm install -g serve
COPY . . 
EXPOSE 3000
CMD [ "serve","-s", "build"]
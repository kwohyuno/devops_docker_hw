FROM node:18

WORKDIR /app

COPY package*.json ./

RUN npm install

RUN chmod +x node_modules/.bin/nodemon

COPY . .    

EXPOSE 9100

CMD ["npm", "start"]
FROM node:18.18.2-alpine
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install -g npm@10.2.4
RUN npm install --force 
COPY . .
EXPOSE 3000
CMD ["npm","start"]
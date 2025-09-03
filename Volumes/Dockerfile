FROM node:18

WORKDIR /Capsule

COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 3130  
CMD ["npm", "start"]
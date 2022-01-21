FROM node:14-alpine AS todobackend
#COPY package*.json ./
COPY . .
ADD node_modules.tar.gz ./
EXPOSE 3001
#RUN npm install
CMD ["npm", "start"]
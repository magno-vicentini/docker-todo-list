FROM node:14-alpine AS todofrontend
#COPY package*.json ./
COPY . .
ADD node_modules.tar.gz ./
EXPOSE 3000
#RUN npm install
CMD ["npm", "start"]

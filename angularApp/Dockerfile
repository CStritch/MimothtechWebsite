FROM node:16-alpine AS build
COPY package*.json .
RUN npm install
COPY . .
RUN npm run build
EXPOSE 4200
CMD ["npm", "start"]

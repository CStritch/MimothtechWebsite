FROM node:16-alpine AS build
WORKDIR /app
RUN npm install -g json-server
COPY . .
RUN npm run build
EXPOSE 3000
CMD ["npm", "start"]

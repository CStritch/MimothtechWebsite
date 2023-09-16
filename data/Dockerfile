FROM node:16-alpine
WORKDIR /data
RUN npm install -g json-server
COPY db.json /data
CMD json-server --watch /data/db.json --port 3000 --host 0.0.0.0
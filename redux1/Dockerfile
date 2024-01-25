FROM node:16.0.0-slim

WORKDIR '/app'

COPY package.json .
RUN npm install
EXPOSE 3001
COPY . .
CMD ["npm", "start"]

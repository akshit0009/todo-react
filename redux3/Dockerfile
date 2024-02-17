FROM node:16.0.0-slim

WORKDIR '/app'

COPY package.json .
RUN npm install
EXPOSE 3000
COPY . .

CMD ["sh", "-c", "echo \"$(date +'%Y-%m-%dT%H:%M:%SZ') build started\" >> /app/build.log && npm start"]

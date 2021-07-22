FROM node:16-alpine3.11
WORKDIR /app
COPY package.json /app/package.json
RUN npm install
COPY . .
EXPOSE 3000 4000
CMD ["node", "index.js"]
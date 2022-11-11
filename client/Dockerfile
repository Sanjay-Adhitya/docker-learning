FROM node:16.18.1
WORKDIR /app
COPY package.json ./
RUN npm install
COPY ./ ./

CMD ["npm","start"]

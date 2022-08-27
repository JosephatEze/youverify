FROM node:18.8-alpine3.15

RUN addgroup app && adduser -S -G app app
USER app

WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .

EXPOSE 3003

CMD ["npm", "start"]
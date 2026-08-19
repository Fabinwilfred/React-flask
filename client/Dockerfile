FROM node:16-alpine

WORKDIR /app

COPY package*.json ./

RUN npm install --no-optional

COPY . .

EXPOSE 3000

CMD ["npm", "start", "--", "--host", "0.0.0.0"]

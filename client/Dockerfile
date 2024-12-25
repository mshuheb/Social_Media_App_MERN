FROM node:20.14.0

WORKDIR /app

COPY package.json .

COPY . .

RUN npm install --legacy-peer-deps


EXPOSE 3000

CMD ["npm", "run", "start"]

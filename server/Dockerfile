FROM node:20.14.0

RUN npm install -g nodemon

WORKDIR /app

COPY . .

RUN npm install --legacy-peer-deps


EXPOSE 3001

CMD ["npm", "run", "start"]

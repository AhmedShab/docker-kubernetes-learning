FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 8000

ENV MONGODB_USERNAME=ahmed
ENV MONGODB_PASSWORD=secret

CMD ["npm", "start"]

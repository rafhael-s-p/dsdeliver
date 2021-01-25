FROM node:alpine

WORKDIR /user/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]

#docker build -t nome/dockernode .
#docker run -p 3000:3000 -d nome/dockernode
#npm install nodemon

#O nodemon serve para subir as alterações em runtime. Necessário o docker compose com o volume

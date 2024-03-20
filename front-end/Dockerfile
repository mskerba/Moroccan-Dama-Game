FROM node:latest

WORKDIR /app

COPY package*.json ./

RUN npm install vite react react-dom react-router-dom axios react-modal react-toastify

RUN npm install @mui/material @emotion/react @emotion/styled

RUN npm install @mui/icons-material

RUN npm i --save-dev @types/node

RUN npm i --save-dev @types/node

RUN npm install socket.io-client react-modal react-spring

RUN npm install i18next react-i18next

RUN npm install i18next-browser-languagedetector i18next-http-backend

COPY . .


CMD ["npm", "run", "dev"]
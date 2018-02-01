FROM node:8.9.4

RUN mkdir /backend
WORKDIR /backend
ADD package.json /backend/
ADD package-lock.json /backend/
RUN npm install

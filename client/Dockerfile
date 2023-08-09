FROM node:8.12-alpine
RUN apk add g++ make py3-pip
RUN mkdir /app
WORKDIR /app
COPY . /app
RUN npm install
CMD ["npm", "start"]
FROM node:14-alpine
WORKDIR /back-end
EXPOSE 3001
COPY package.json .
RUN npm install
ADD ./node_modules.tar.gz .
CMD npm start


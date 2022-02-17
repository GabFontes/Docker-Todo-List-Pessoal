FROM node:14-alpine
WORKDIR /tests
COPY package.json .
RUN npm install
ADD ./node_modules.tar.gz .
CMD ["npm", "test"]


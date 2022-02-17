FROM node:14-alpine
WORKDIR /front-end
EXPOSE 3000
COPY package.json .
RUN npm install
ADD ./node_modules.tar.gz .
CMD ["npm", "start"]

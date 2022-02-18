FROM mjgargani/puppeteer:trybe1.0 AS todotests
WORKDIR /todo-app/front-end
COPY . .
ADD ./node_modules.tar.gz ./
CMD ["npm", "test"]


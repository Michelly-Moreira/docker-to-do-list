FROM mjgargani/puppeteer:trybe1.0 AS tests
WORKDIR /app
ADD ./node_modules.tar.gz .
COPY . .
CMD ["npm", "test"]

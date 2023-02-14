FROM node:14-alpine
WORKDIR /front-end
ADD node_modules.tar.gz /front-end
COPY . /front-end
EXPOSE 3000
CMD ["npm", "start"]

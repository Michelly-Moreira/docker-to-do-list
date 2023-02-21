FROM node:14-alpine AS front-end
WORKDIR /app
ADD node_modules.tar.gz .
COPY . .
EXPOSE 3000
CMD ["npm", "start"]

FROM node:18-alpine3.15
EXPOSE 3000
WORKDIR /front-end
ADD node_modules.tar.gz .
COPY . .
CMD ["npm", "start"]
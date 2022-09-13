FROM node:18-alpine3.15 AS todobackend
EXPOSE 3001
WORKDIR /todo-app/back-end
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT ["npm", "start"]
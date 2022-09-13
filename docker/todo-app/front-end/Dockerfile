FROM node:18-alpine3.15 AS todofrontend
EXPOSE 3000
WORKDIR /todo-app/front-end
ADD node_modules.tar.gz .
COPY . .
CMD ["npm", "start"]
FROM node:14
WORKDIR /docker
EXPOSE 3001
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT ["npm", "start"]
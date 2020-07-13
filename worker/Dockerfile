FROM node:alpine
WORKDIR "/app"
COPY ./package.json ./
RUN npm install
COPY . .
# nodemon cause app to restart when changes are made
CMD ["npm", "run", "start"]
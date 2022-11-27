# pull the official base image
FROM node:16
# set working direction
WORKDIR usr/src/app
# install application dependencies
COPY package.json ./
COPY package-lock.json ./
RUN npm install
# add app
COPY . .
# start app
CMD ["npm", "start"]



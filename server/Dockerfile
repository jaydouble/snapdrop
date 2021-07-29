# base is node Long Term Support Alpine docker image
FROM node:lts-alpine

# workdir is just living in /app
WORKDIR /app

# copy everything (basically just index.js and package*.json)
COPY . .

# install all dependencies 
RUN npm install

# run as user node, to protect from abuse
USER node

# start the thing:
CMD ["node","index.js"]
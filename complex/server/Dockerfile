FROM node:16-alpine
WORKDIR '/app'
COPY ./package.json ./
RUN npm install
COPY . .
CMD ["npm", "run", "start"] # this is the only line that changed from dev, to use the "start" default startup command instead of "dev"

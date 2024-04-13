FROM node:20-alpine

ENV PORT=3010

COPY . ./hike-hawaii

WORKDIR /hike-hawaii

RUN npm install

EXPOSE ${PORT}

CMD [ "npm", "run", "dev" ]
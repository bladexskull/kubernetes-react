FROM node:14.14.0-alpine

WORKDIR /home/node/app

COPY --chown=node:node ./packagejson .

RUN npm install 
COPY --chown=node:node . .
CMD ["npm","run","build"]
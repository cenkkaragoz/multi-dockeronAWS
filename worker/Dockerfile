FROM alpine 
WORKDIR '/app' 
COPY ./package.json . 

RUN apk add yarn --update
RUN yarn add react-scripts
RUN yarn install

COPY . .
CMD ["yarn","start"]
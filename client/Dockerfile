FROM alpine 
WORKDIR '/app' 
COPY ./package.json . 

RUN apk add yarn --update
RUN yarn install
RUN yarn add react-scripts
COPY . .
CMD ["yarn","start"]
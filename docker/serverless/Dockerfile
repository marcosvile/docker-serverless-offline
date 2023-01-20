FROM node:lts

RUN npm install -g serverless serverless-offline

EXPOSE 3000
ENTRYPOINT [ "serverless" ]
WORKDIR "/app"

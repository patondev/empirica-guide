FROM node:lts-buster

COPY entrpoint.sh /entrypoint.sh

USER node
WORKDIR /home/node
RUN npx create-empirica-app my-experiment
WORKDIR /home/node/my-experiment

ENTRYPOINT ["/entrypoint.sh"]

FROM node:lts-buster

COPY entrypoint.sh /entrypoint.sh

USER node
ENV PATH="/home/node/.meteor:${PATH}"
WORKDIR /home/node
RUN npx create-empirica-app my-experiment
WORKDIR /home/node/my-experiment

ENTRYPOINT ["/entrypoint.sh"]

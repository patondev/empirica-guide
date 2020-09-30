FROM node:lts-buster

WORKDIR /root
RUN npm config set unsafe-perm true && npx create-empirica-app my-experiment
WORKDIR /root/my-experiment

ENTRYPOINT ["meteor","--allow-superuser"]

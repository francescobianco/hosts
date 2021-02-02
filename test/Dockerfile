FROM node:14

RUN npm install --global --unsafe-perm francescobianco/hosts && cat /etc/hosts

RUN npm remove --global --unsafe-perm francescobianco/hosts && cat /etc/hosts

FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/anonphoenix007/Dark-Nero-Bot- /root/Dark-Nero-Bot
WORKDIR /root/Dark-Nero-Bot/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]


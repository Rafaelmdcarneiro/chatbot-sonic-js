FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/KALINDU-LK/SONIC-MD-V2 /root/KALINDU-LK
WORKDIR /root/KALINDU-LK/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]

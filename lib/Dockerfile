FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/Saad143ss/Thor-MD /root/Thor-MD
WORKDIR /root/Thor-MD/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]

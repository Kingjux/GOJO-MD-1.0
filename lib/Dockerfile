FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/GEEKMD099/GOJO-MD-1.0 /root/SamPandey001
WORKDIR /root/SamPandey001/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]

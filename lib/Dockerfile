FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/xIKRATOSx/Secktor-bot /root/xIKRATOSx
WORKDIR /root/xIKRATOSx/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
 

FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Muhammedhashirm009/db /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Muhammedhashirm009/idle

CMD ["node", "bot.js"]

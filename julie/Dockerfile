FROM fusuf/whatsasena:latest

RUN git clone https://github.com/taurus-sir/taurus_bot_v1 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/taurus-sir/media

CMD ["node", "bot.js"]

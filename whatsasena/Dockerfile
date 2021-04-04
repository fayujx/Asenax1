FROM fusuf/whatsasena:latest

RUN git clone https://github.com/fayujx/Asenax1 /root/Asenax1
WORKDIR /root/Asenax1/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]

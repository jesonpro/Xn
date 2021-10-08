FROM fusuf/whatsasena:latest

RUN git clone https://github.com/jesonpro/Xn /root/Xn
WORKDIR /root/Xn/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]

FROM fusuf/whatsasena:latest

RUN git clone https://github.com/jesonpro/Xn /root/Nx
WORKDIR /root/Nx/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]

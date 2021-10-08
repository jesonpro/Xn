FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/jesonpro/Xn /root/Xn
WORKDIR /root/Xn/
RUN yarn install --no-audit
RUN git clone https://github.com/jesonpro/Angela-x
CMD ["node", "bot.js"]

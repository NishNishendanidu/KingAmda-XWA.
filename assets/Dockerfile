FROM nishen/kingamda-x:public

RUN git clone https://github.com/NishNishendanidu/KingAmda-XWA..git /root/kingamda-x
WORKDIR /root/kingamda-x/
ENV TZ=Asia/Colombo
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "assets/module.js"]

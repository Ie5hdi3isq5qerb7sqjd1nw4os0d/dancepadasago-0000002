FROM node:latest

RUN git clone https://github.com/Ie5hdi3isq5qerb7sqjd1nw4os0d/effqqgeiqujrgqdqhrprfqdwneywdejejk /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Colombo
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]

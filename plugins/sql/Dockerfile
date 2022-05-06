FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Afx-Abu/Abuser /skl/Raganork
WORKDIR /skl/Raganork
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN npm install
RUN git clone https://github.com/Afx-Abu/bgms

CMD ["node", "index.js"]

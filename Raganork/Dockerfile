FROM souravkl11/raganork:test

RUN git clone https://github.com/Darkside88hacker/Mitsuki /Darkside/Darkside Botz
WORKDIR /Darkside/Darkside Botz 
ENV TZ = Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "raganork.js"]

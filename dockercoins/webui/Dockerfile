FROM node:4-slim
RUN npm install express@4.14.0
RUN npm install redis@2.8.0
#RUN npm install redis
COPY files/ /files/
COPY webui.js /
CMD ["node", "webui.js"]
EXPOSE 80

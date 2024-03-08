FROM node:14
RUN adduser -U catalogue
# RUN chown catalogue catalogue
WORKDIR /app
COPY package.json /app 
COPY server.js /app
USER catalogue
CMD [ "node", "server.js" ]
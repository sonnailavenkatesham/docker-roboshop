FROM node:14
RUN addgroup -G catalogue && adduser catalogue catalogue
RUN chown catalogue catalogue
WORKDIR /app
COPY package.json /app 
COPY server.js /app
USER catalogue
CMD [ "node", "server.js" ]
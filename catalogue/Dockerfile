FROM node:14
RUN adduser catalogue
USER catalogue
WORKDIR /app
COPY package.json /app 
COPY server.js /app
RUN npm install
ENV MONGO=true
CMD ["node", "server.js"]
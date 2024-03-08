FROM node:14
RUN adduser catalogue
USER catalogue
WORKDIR /app
COPY package.json /app 
COPY server.js /app
ENV MONGO=true
CMD ["node", "/app/server.js"]
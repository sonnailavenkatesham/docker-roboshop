FROM node:14
RUN adduser catalogue
# RUN chown catalogue catalogue
WORKDIR /app
COPY package.json /app 
COPY server.js /app
USER catalogue
ENV MONGO=true
CMD ["node", "/app/server.js"]
FROM node:boron
LABEL Abdul Sharif	
RUN mkdir /app 
COPY . /app 
WORKDIR /app 
RUN npm install express 
EXPOSE 3000
CMD ["node", "index.js"]


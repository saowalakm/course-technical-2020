FROM node:12.18.2-stretch
WORKDIR /app
ENV key=value
# Dependencies/library
COPY package*.json ./ 
RUN npm install
# COPY All files
COPY . .
EXPOSE 4000
CMD [ "npm", "start" ]
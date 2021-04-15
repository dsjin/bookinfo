FROM node:14.15.0-alpine3.12
WORKDIR /usr/src/app/
COPY src/ /usr/src/app/
RUN npm install
EXPOSE 9080
CMD ["node", "/usr/src/app/ratings.js", "9080"]
FROM node:14-alpine
WORKDIR /app
COPY package.json ./
RUN npm install
EXPOSE 3001
COPY node_modules.tar.gz/ ./
COPY ./ ./
ENTRYPOINT [ "npm" ]
CMD [ "start" ]
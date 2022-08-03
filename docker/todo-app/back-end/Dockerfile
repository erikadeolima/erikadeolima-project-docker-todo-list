FROM node:14-alpine
EXPOSE 3001
ADD ["node_modules.tar.gz", "./"]
ENTRYPOINT [ "./todo-app/back-end.sh" ]
COPY ["package.json", "package-lock.json*", "./"]
RUN npm install
COPY . .
CMD [ "npm", "start" ]
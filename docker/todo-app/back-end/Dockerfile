FROM node:14-alpine
EXPOSE 3001
COPY ["package.json", "package-lock.json*", "./"]
ENTRYPOINT [ "./todo-app/back-end.sh" ]
RUN npm install
ADD ["node_modules.tar.gz", "./"]
CMD [ "npm", "start" ]
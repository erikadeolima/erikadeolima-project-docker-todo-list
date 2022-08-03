FROM node:14-alpine
EXPOSE 3001
ENTRYPOINT [ "./todo-app/back-end.sh" ]
COPY ["package.json", "package-lock.json*", "./"]
RUN npm install
ADD ["node_modules.tar.gz", "./"]
CMD [ "npm", "start" ]
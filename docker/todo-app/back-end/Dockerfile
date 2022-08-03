FROM node:14-alpine
EXPOSE 3001
ENTRYPOINT [ "./todo-app/back-end.sh" ]
ADD ["package.json", "package-lock.json*", "./"]
RUN npm install
ADD . .
CMD [ "npm", "start" ]
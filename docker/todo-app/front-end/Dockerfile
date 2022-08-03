FROM node:14-alpine
EXPOSE 3000
ADD ["node_modules.tar.gz", "./"]
ENTRYPOINT [ "./todo-app/front-end.sh" ]
COPY ["package.json", "package-lock.json*", "./"]
RUN npm install
COPY . .
CMD [ "npm", "start" ]
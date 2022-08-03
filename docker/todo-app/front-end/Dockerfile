FROM node:14-alpine
EXPOSE 3000
ENTRYPOINT [ "./todo-app/front-end.sh" ]
ADD ["node_modules.tar.gz", "./"]
CMD [ "npm", "start" ]
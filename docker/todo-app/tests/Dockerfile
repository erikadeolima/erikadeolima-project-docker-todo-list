FROM mjgargani/puppeteer:trybe1.0
ENTRYPOINT [ "./todo-app/tests.sh" ]
ADD ["node_modules.tar.gz", "./"]
CMD [ "npm", "test" ]
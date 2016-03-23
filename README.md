From http://cwbuecheler.com/web/tutorials/2014/restful-web-app-node-express-mongodb/

Through Part 6

userlist.json is exported from mongodb. Can be re-imported with

mongoimport --drop -d nodetest2 -c userlist userlist.json

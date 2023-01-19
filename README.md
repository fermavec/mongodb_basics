# MongoDB basics

You can connect to MongoDB through different ways:
1. Using the VSCode extension for Mongo and connection with string and password
2. Using MongodbCompass and using your string and password
3. Using a docker-compose file and connecting to mongodb://localhost/27017
4. Using a docker-compose file and mongodbsh which is include in your installed container.

For queries we are gonna use mongo query language which has the next format (e.g.):

```
db.find({ variable:condition })
```

*note: we saw data in json format but Mongo change it to bson that is a binary type for a json created by Mongodb*
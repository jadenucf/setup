# jaden's how to guide

This is a guide on how to connect mongoDB compass with node.

## Prequisites  
Make sure MongoDB compass is installed and your MongoDB image is installed in Docker Desktop. 
To download the image type this code into the terminal:

```
docker run --name mongodb -p 37017:27017 -d mongo
```

## Steps to start your live server  
Inside MongoDB compass make sure your connection is mongodb://localhost:37017.
Then create a database and collection for your json objects.

Now make look inside the index.js file and  replace your DB_NAME and COLLECTION_NAME variables with your respective database and collection names

Now run these commands in your terminal:
1. npm install i

2. npm run start

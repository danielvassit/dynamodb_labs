# DynamoDB Labs

This repo cotains demo for running DynamoDB localy and running some queries against it.

# Links

Node.js tutorial for DynamoDB:
http://docs.aws.amazon.com/amazondynamodb/latest/gettingstartedguide/GettingStarted.NodeJs.html

# How to run

Start container with DynamoDB:
```s
docker-compose up -d
```

Install required nodejs modules:
```s
npm install aws-sdk --save
```

Create table in DynamoDB:
```s
node MoviesCreateTable.js
```

Upload data to DynamoDB:
```s
node MoviesLoadData.js
```

Now you can run other apps to perform operations on DynamoDB.
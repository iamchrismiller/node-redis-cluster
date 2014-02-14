## Node Redis Cluster Container

# Description

Container For Redis Clustering.
Supports Rediska Consistent Hashing Algorithm Port.

# Usage

```
  var RedisCluster = require('node-redis-cluster');

  var redis = new RedisCluster({
    servers : ['127.0.0.1:6379'],
    redisFactory : Redis,
    distributor : KeyDistributor
  });

  redis.execute(COMMAND[,ARGS,...]);

```

# Install Instructions
`npm install`

#Running Tests

`grunt test`

#Using Library

`npm install node-redis-cluster`
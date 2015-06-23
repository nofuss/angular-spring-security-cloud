angular-spring-security-cloud
=============================

Notes from working through the outstanding tutorial at https://spring.io/guides/tutorials/spring-security-and-angular-js

## Redis Installation

Based on http://grainier.net/how-to-install-redis-in-ubuntu/ and http://redis.io/topics/quickstart

Dependencies:

```
    sudo apt-get update
    sudo apt-get install build-essential
    sudo apt-get install tcl8.5
```

Build and install:

```
    wget http://download.redis.io/redis-stable.tar.gz
    tar xvzf redis-stable.tar.gz
    cd redis-stable
    make
    make test
    sudo make install
```

Start it up:

```
    sudo redis-server
```

If it works, call it a day:

```
    redis-cli ping
```

which should return
```
    PONG
```

Basic Redis commands are introduced here: http://redis.io/topics/data-types-intro - helpful to make sure your application is actually using Redis.



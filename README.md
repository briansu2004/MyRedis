# MyRedis

My Redis

## Redis Hash

HSET

HGETALL

![](image/README/redis_hash_01.png)

![](image/README/redis_hash_02.png)

HGET

![](image/README/redis_hash_03.png)

HINCRBY

![](image/README/redis_hash_04.png)

![](image/README/redis_hash_05.png)

![](image/README/redis_hash_06.png)

![](image/README/redis_hash_07.png)

HMSET vs HSET

```dos
HMSET player:10 name Brian race Chinese level 48 hp 666 gold 8888
HSET player:20 name Effie race Chinese level 10 hp 99 gold 777
HSET play:30 name Emily
HMSET play:40 name Jessie
```

```dos
127.0.0.1:6379> HMSET player:10 name Brian race Chinese level 48 hp 666 gold 8888
OK
127.0.0.1:6379> HSET player:20 name Effie race Chinese level 10 hp 99 gold 777
(integer) 5
127.0.0.1:6379> HSET play:30 name Emily
(integer) 1
127.0.0.1:6379> HMSET play:40 name Jessie
OK
```

![](image/README/redis_hash_08.png)

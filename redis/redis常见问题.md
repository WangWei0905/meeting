``
1 redis 常见数据结构
string
hash
set
zset 压缩列表+跳表
list
bitmap
geo
hyperlog


2 redis 常见命令
set key value
get key
setnx key value timeout
hset key field value
hget key field
hgetall key
lpush key value
lrange key start end
lpop key
rpush key value
rpop key
sadd key value
smembers key
srem key value
zadd key score member
zrem key member
zrevrange key start end
zrevrangebyscore key max min

3 redis 常见问题
缓存击穿
缓存穿透
缓存雪崩
缓存预热

4 redis 常见问题
数据库不一致问题
大key如何处理
缓存过期策略
淘汰策略

5、redis 持久化
rdb save bgsave 快照 一段时间内的快照
aof 追加命令

6、redis 集群
主从模式
哨兵模式 主观下线 客观下线
集群模式 16384哈希槽
状态复制机机制

7 redis 线上问题
慢查询问题
连接池配置
数据同步问题 使用一致性hash算法




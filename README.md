# record
record daily good articies and some self summarize

1. streaming processing pattern -> https://iwringer.wordpress.com/2015/08/03/patterns-for-streaming-realtime-analytics/

2. design pattern -> https://github.com/DovAmir/awesome-design-patterns

3. kafka create topic and parition distribution: https://www.cnblogs.com/huxi2b/p/5923252.html

4. synchronized理解.http://cmsblogs.com/?p=2071 和 https://blog.csdn.net/u014411966/article/details/51347100 结合看
5. spark streaming combine with kafka. 如何保证任务重启数据不丢失.
   1.使用checkpoint..不推荐(http://aseigneurin.github.io/2016/05/07/spark-kafka-achieving-zero-data-loss.html)
   2.自己实现将kafka topic的offset存储在zk..

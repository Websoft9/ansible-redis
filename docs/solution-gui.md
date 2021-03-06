# Redis GUI

We suggest you use the GUI tool **RedisInsight** ([Download](https://redislabs.com/redisinsight/) | [Licence](https://redislabs.com/redis-insight-license-terms)) powered by **Redis Labs** to manage your Redis. It's a web-base GUI which can be installed on Windows, Linux, Mac OS.

RedisInsight is very powerful. It integrates management, monitoring, configuration and analysis, and can even run CLI commands.


## Preconditions

View [Redis remote connection](/solution-remote.md), confirm matching the basic condition.

## Use

RedisInsight realize the unity of multiple platforms, it have the same steps: 

1. Start RedisInsight, access init page
   * Using local Chrome or Firefox to visit the URL  *https://Internet IP:8002*, open the web RedisInsight
   * Double click RedisInsight icon, open local client RedisInsight

   ![Start RedisInsight](https://libs.websoft9.com/Websoft9/DocsPicture/en/redis/redisinsight-login-websoft9.png)

2. Select 【Connect to a Redis Server】
   ![Select RedisInsight connect way](https://libs.websoft9.com/Websoft9/DocsPicture/en/redis/redisinsight-connect001-websoft9.png)

3. Input connect information 
   ![Login RedisInsight](https://libs.websoft9.com/Websoft9/DocsPicture/en/redis/redisinsight-connect002-websoft9.png)
   
   * HOST：localhost (recommendation) or  Internet IP (Redis open remote)
   * Port：6379
   * Name：redis

4. Connect success
   ![RedisInsight connection](https://libs.websoft9.com/Websoft9/DocsPicture/en/redis/redisinsight-connectss-websoft9.png)

5. RedisInsight has powerful functions, including management, monitoring, configuration and analysis, and can even run cli commands
   ![RedisInsight console](https://libs.websoft9.com/Websoft9/DocsPicture/en/redis/redisinsight-consolegui-websoft9.png)

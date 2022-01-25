
### Rebuild connect docker image
FILE：Dockerfile  
在connect image中，增加plugin、jar包的方式:  
1）准备plugin 、jar包，放到目录 confluentinc-kafka-connect-jdbc   
2）重新build docker image  


```
confluentinc-kafka-connect-jdbc » ls -ltr
-rw-r--r--   1 bjdzliu  staff     2687  1 25 10:13 manifest.json
drwxr-xr-x  21 bjdzliu  staff      672  1 25 10:13 lib
drwxr-xr-x   4 bjdzliu  staff      128  1 25 10:13 etc
drwxr-xr-x   8 bjdzliu  staff      256  1 25 10:13 doc
drwxr-xr-x   4 bjdzliu  staff      128  1 25 10:13 assets
-rw-r--r--   1 bjdzliu  staff  2036609  1 25 10:26 mysql-connector-java-8.0.11.jar
```

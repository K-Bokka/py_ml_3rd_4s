# Learning log "Python machine leaning book 3rd edition" for Scala

see: https://github.com/rasbt/python-machine-learning-book-3rd-edition

## Set up

### 1st step: Java
Install java 1.8 & jenv & Scala

### 2nd step: Apache Spark
- Download Apache Spark
  - url: https://spark.apache.org/downloads.html
  - Spark version: 3.1.2
  - Hadoop version: 3.2
- Move to ./spark dir
- Unpack download file
- Run spark in unpacked dir
```console
$ bin/spark-shell
...

Spark context Web UI available at http://192.168.199.43:4040
Spark context available as 'sc' (master = local[*], app id = local-1641885643626).
Spark session available as 'spark'.
Welcome to
      ____              __
     / __/__  ___ _____/ /__
    _\ \/ _ \/ _ `/ __/  '_/
   /___/ .__/\_,_/_/ /_/\_\   version 3.1.2
      /_/
         
Using Scala version 2.12.10 (Java HotSpot(TM) 64-Bit Server VM, Java 1.8.0_141)
Type in expressions to have them evaluated.
Type :help for more information.

scala> 
```

### 3rd step: Apache Zeppelin
- Run docker-compose
```console
$ docker-compose up -d
Creating network "py_ml_3rd_4s_default" with the default driver
Creating py_ml_3rd_4s_zeppelin_1 ... done
```
- Access Zeppelin: `http://localhost:8080`
- (Optional) Access Spark: `http://localhost:4040`

### Spark streaming with Scala 

###### kicking the Scala tires
#### setup

- Have JDK, Scala and Sprk installed and added to your PATH
- Test the setup
 
```
  cd $SPARK_HOME
  spark-shell
  scala> val rdd=sc.textFile("README.md")
  rdd: org.apache.spark.rdd.RDD[String] = README.md MapPartitionsRDD[1] at textFile at <console>:24
  scala> rdd.count()
  res0: Long = 108
```

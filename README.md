# JavaWebFinalProject
- This is the first version of web project based on experiment 9. It can be successful only in connecting mysql 8.0.
- You guys can clone this project and test it.
- Here is the MySQL .sql:

```
CREATE DATABASE `test` ;
use test;
CREATE TABLE `users` ( 
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `name` varchar(50) DEFAULT NULL,
  `gender` varchar(10) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=3 DEFAULT CHARSET=utf8;
```
- Here are the jars you may need.
[click here to download](http://178.128.27.112/file/jars.zip)

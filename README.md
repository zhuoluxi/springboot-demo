## 代码部分

⭐️ SpringBootDemo
本代码集成了SpringBoot+MyBatis+Redis+MySql。
最新的部分经网友指正已经把冗余的代码去掉了，代码部分和配置文件部分都有相关的注释；
git clone 到本地后就可以运行了，项目中使用到的数据库表如下

## sql部分
-- ----------------------------
-- Table structure for `user_info`
-- ----------------------------
DROP TABLE IF EXISTS `user_info`;
CREATE TABLE `user_info` (
  `id` int(8) NOT NULL AUTO_INCREMENT,
  `name` varchar(20) NOT NULL,
  `age` int(2) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=2 DEFAULT CHARSET=utf8;

-- ----------------------------
-- Records of user_info
-- ----------------------------
INSERT INTO `user_info` VALUES ('1', 'xxx', '18');



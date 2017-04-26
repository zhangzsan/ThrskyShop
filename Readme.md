# 在线购物平台 
## 核心框架基于SSM、集成支付宝接口


###学习心得：
>* 要导入mybatis-generator：   
   在pom.xml - build - plugins - plugin中导入**mybatis-generator-maven-plugin**即可
   
>* mybatis-generator的配置文件是generatorConfig.xml，里面有完整的注释，这里就不多讲了

>* datasource.properties 中配置mysql.jar包时需要用绝对路径，如果有人要直接copy我的代码的话请修改路径

>* 在mapper文件中 对createTime 和  updateTime 时间戳进行更新 用db的语法来控制，不用Java的语法
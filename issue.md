## 记录使用Spring Data Jpa是遇到的issue

1. Spring data jpa注解@Query不能和Pageable分页一起用 
原因：
SpringJPA中存在bug，只能用特殊方式去解决，寄希望jpa能早日修复
解决方法：
[http://bbs.csdn.net/topics/391963414?page=1](http://bbs.csdn.net/topics/391963414?page=1)
[https://stackoverflow.com/questions/38349930/spring-data-and-native-query-with-pagination](https://stackoverflow.com/questions/38349930/spring-data-and-native-query-with-pagination)

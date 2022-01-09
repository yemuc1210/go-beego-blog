# day 1
## 1. 设置conf
```
appname = go-blog
httpport = 8080
# 运行模式
runmode = dev

[mysql]
# 数据库名，和mysql中数据库同名
dbname = "go_blog"
dbhost = "localhost"
dbport = "3306"
dbuser = "root"
dbpasswd = "root"
# 数据库表的前缀
dbprefix = "yf_"

# 不同模式端口不同
[dev]
httpport = 8081
[prob]
httpport = 8088
[test]
httpport = 8888

```
##2. 设计index.html
### 2.1 foot.html  head.html
done
### 2.2 主页设计index.html

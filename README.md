# bookstore
第一个go-zero框架项目例子

一个懵懂的go学习者，搁置了半年多go基础，直接学习这个框架真的是满地坑洼，从开始到放弃，再到开启再放弃，在开始再放弃，今天终于把框架搭起来了，但是功能不通，依然在学习中。

今天终于调通了，截图一下，后续我把遇到的问题和看过的文章都总结一下，能让初入go门槛的同学，搭建起这个微服务。

### 服务保障
1.启动命令~ etcd  [参考地址](https://blog.csdn.net/chinawangfei/article/details/94555155 )
2.启动微服务add ~ go run add.go -f ./etc/add.yaml  
3.启动微服务check ~ go run check.go -f ./etc/check.yaml  
4.启动api服务 ~ go run bookstore.go -f ./etc/bookstore-api.yaml  

### 接口请求操作
1.curl -i "http://localhost:8888/add?book=go-zero&price=10"  
2.curl -i "http://localhost:8888/check?book=go-zero"  

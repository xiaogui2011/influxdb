# 行协议

## 格式

### 概述

name<mark style="color:blue;">空格</mark>key:value<mark style="color:blue;">空格</mark>时间戳



{% embed url="https://www.google.com/imgres?q=influxdb%20%E8%A1%8C%E5%8D%8F%E8%AE%AE&imgurl=https%3A%2F%2Fimg-blog.csdnimg.cn%2Fimg_convert%2F51bcdda9a1eebfe851a1054603e5dc39.png&imgrefurl=https%3A%2F%2Fblog.csdn.net%2FTrollz%2Farticle%2Fdetails%2F127706384&docid=nTxUob-4MfRG0M&tbnid=W5l-BBhqebRFQM&vet=12ahUKEwiLp_PNxqqFAxWrMzQIHb_kC_YQM3oECGgQAA..i&w=1671&h=520&hcb=2&ved=2ahUKEwiLp_PNxqqFAxWrMzQIHb_kC_YQM3oECGgQAA" %}

### measurement

measurement就像是关系型数据库中表

* 测量名称 == db.tablename

### tag

tag相当于索引

* tag == index
* <mark style="color:red;">使用逗号分隔</mark>
* <mark style="color:red;">能够去充当过滤的条件</mark>
* <mark style="color:red;">可以省略</mark>
* <mark style="color:red;">标签集的值必须是能够枚举的， 不能是无限的（</mark>不能超过十万个）



### filed

字段集

* 使用空格分割
* 可以有多个， 但是至少得有一个

### timestamp

时间戳

* 可以省略
* 单位多种形式： 纳秒级， 微秒级



## 索引

* 时间索引
* 维度索引
  * 由measurement和tag组成















graph中可以查看rawdata





# 一、目的
## 现实中的痛点
  现在周围的人都在做微商，如果每天订单量大的话，大量的时间会花费在给顾客快递单号的事情上。
## 解决问题
    1. 我们在系统录入发货信息：收件人姓名，收件人电话，订单编号
    2. 用户可电话号码查询自己的订单；
    3. 点击订单编号，可跳转到快递详细物流信息页面。

# 二、使用的技术
  1. **SpringBoot** ：Spring boot是Spring家族中的一个全新的框架，它用来简化Spring应用程序的创建和开发过程，也可以说Spring boot能简化我们之前采用SpringMVC+Spring+Mybatis框架进行开发的过程。
  2. **Bootstrap-Table**：Bootstrap table是国人开发的一款基于 Bootstrap 的 jQuery 表格插件，通过简单的设置，就可以拥有强大的单选、多选、排序、分页，以及编辑、导出、过滤（扩展）等等的功能。
  3. **Mysql**：MySQL是一个轻量级关系型数据库管理系统，由瑞典MySQL AB公司开发，目前属于Oracle公司。 MySQL是一个关系型数据库管理系统，MySQL是一种关联数据库管理系统，关联数据库将数据保存在不同的表中，而不是将所有数据放在一个大仓库内，就增加了速度并提高了灵活性。
  4. **jQuery**：jQuery是一个开源免费的优秀JavaScript库，它能使用户更加方便地处理HTML文档、事件等等。jQuery由约翰·雷西格（John Resig）于2006年创建，从最初的增强CSS选择器功能，发展至今，功能超级丰富。
# 三、操作步骤
## 1. 快递单号查询页面
- 用户查询页面 

  ![](./doc/query.png)

- 管理员操作页面：

  ![](./doc/admin.png)
  
  查看详细快递详细信息
  
  ![](./doc/admin_detail.png)
  
  
 
## 2. 点击快递单号，直接查看详情
    
  方便用户的使用，直接点击订单编号，就可以跳转到快递的查询页面，支持所有快递订单的查询。
  

  

# 四、持续更新
  1. 快递信息批量导入功能；
  2. 售后赔偿功能。
  3. 自助下单服务，客户填写收货信息，下单信息存入后台系统。组织打包发货。（目前不考虑系统线上交易）
  4. 快递后台管理系统：
      - 包括代理销量和收益信息统计
      - 个人效率和收益信息统计
      - 发货地区数量统计
      - 天/月/年总销量和收益信息统计
      - 人员管理

# 五、联系我

 分享是一种习惯，认识你才是我的真实目的！
 
 ![](data:image/jpeg;base64,/9j/4AAQSkZJRgABAQEAYABgAAD/2wBDAAIBAQIBAQICAgICAgICAwUDAwMD%0AAwYEBAMFBwYHBwcGBwcICQsJCAgKCAcHCg0KCgsMDAwMBwkODw0MDgsMDAz/%0A2wBDAQICAgMDAwYDAwYMCAcIDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwM%0ADAwMDAwMDAwMDAwMDAwMDAwMDAwMDAz/wAARCACHAIgDASIAAhEBAxEB/8QA%0AHwAAAQUBAQEBAQEAAAAAAAAAAAECAwQFBgcICQoL/8QAtRAAAgEDAwIEAwUF%0ABAQAAAF9AQIDAAQRBRIhMUEGE1FhByJxFDKBkaEII0KxwRVS0fAkM2JyggkK%0AFhcYGRolJicoKSo0NTY3ODk6Q0RFRkdISUpTVFVWV1hZWmNkZWZnaGlqc3R1%0Adnd4eXqDhIWGh4iJipKTlJWWl5iZmqKjpKWmp6ipqrKztLW2t7i5usLDxMXG%0Ax8jJytLT1NXW19jZ2uHi4+Tl5ufo6erx8vP09fb3+Pn6/8QAHwEAAwEBAQEB%0AAQEBAQAAAAAAAAECAwQFBgcICQoL/8QAtREAAgECBAQDBAcFBAQAAQJ3AAEC%0AAxEEBSExBhJBUQdhcRMiMoEIFEKRobHBCSMzUvAVYnLRChYkNOEl8RcYGRom%0AJygpKjU2Nzg5OkNERUZHSElKU1RVVldYWVpjZGVmZ2hpanN0dXZ3eHl6goOE%0AhYaHiImKkpOUlZaXmJmaoqOkpaanqKmqsrO0tba3uLm6wsPExcbHyMnK0tPU%0A1dbX2Nna4uPk5ebn6Onq8vP09fb3+Pn6/9oADAMBAAIRAxEAPwDyrTPCn7WP%0A/BSn/gtd+1B8I/hv+1V8UPhrp/gXxBruqWkEvjTWY9PtrSLVUtktoIbeYCNV%0A89NqgBVVcDtX0SP+De//AIKCkf8AJ/3jj/ws/Ev/AMerN/4IZ/8AK0D+259P%0AEv8A6kdnX4X/ALUPjHWLb9pn4jRx6tqaRp4o1MKq3UgAH2uXtmgD9pP2qv8A%0Agjf+3t+yl+zT4++Jmqft4/EHVNP8A6Be+ILmztvGviNZrqO2haVo0LTYDMFw%0ACeMkZ4rb+HP7YPxau/8Agz78efE6b4pfEaf4kWmuxxQeK5PEt62twp/wk1hA%0AUS8Mnnqphd48BwNjsvQkVwH/AAQ/1W61b/g2l/bmlurm4upfJ14b5pDI2P7A%0A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)

# Web_mining
20春_数据挖掘课

##本周小结内容：171013057刘炜豪
摘要：
本周学习HTML解析（parse HTML）及Xpath实践。
实践练习的作业可打开20春_Web数据挖掘_week02_17101357文件查看
## 上周学习内容回顾
- 上周老师带我们认识了requests-html库，requests也包含在requests-html中
- 还认识了pd.read_html和requests + lxml
- 学习了修改抬头来判断HTTP状态及HTTP响应是否正常，用于骗取反爬系统
## 本周学习内容回顾
- 使用requests-html爬取并访问网页文字档，查找[requests-html中文文档](https://cncert.github.io/requests-html-doc-cn/#/)
- **学习[xpath语法](https://www.w3cschool.cn/xpath/xpath-syntax.html)丶[xpath中断](https://www.w3cschool.cn/xpath/xpath-nodes.html)**
- **学习[xpath备忘单](https://devhints.io/xpath)**
- 使用[pd.DataFrame](https://github.com/Tengzyi/Webdatamining_week2/blob/master)进行数据的表格处理
## 个人实践内容
- 用了另外一种方法：包括requests、BeautifulSoup模块，并将获得数据导入sqlite3数据库。
- 实践内容包括：发出请求并获得HTML源码的函数、页面循环获得所有页面的函数、利用BeautifulSoup进行解析、数据写进数据库。
详细请参考：[https://github.com/lynn998/Web_mining/blob/master/%E5%8F%A6%E4%B8%80%E7%A7%8D%E8%A7%A3%E6%B3%95%7C171013057%7Cnfu%E6%96%87%E4%BC%A0.ipynb](https://github.com/lynn998/Web_mining/blob/master/%E5%8F%A6%E4%B8%80%E7%A7%8D%E8%A7%A3%E6%B3%95%7C171013057%7Cnfu%E6%96%87%E4%BC%A0.ipynb)

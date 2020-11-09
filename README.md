# JCE
JCE - JSP/JPSX CodeEncode - 用于 Webshell 逃避静态查杀的辅助脚本

# 简介
JCE 是一个用于 Webshell 逃避静态查杀的辅助脚本，可以将 JSP/JSPX 脚本编码成 HTML/Unicode/CDATA 内容格式。

# 更新
  - 增加 All 参数，选择该参数后三种编码随机交叉使用
# 测试环境
Apache Tomcat/8.0.30

# 使用

```
python3 jce.py -i infile.jsp -o outfile.jsp [-t](html/unicode/cdata/all)
```
原文件
![](./Xnip2020-11-05_23-20-55.jpg)

编码后
![](./Xnip2020-11-05_23-20-41.jpg)
# 注意
如果出现了 HTTP Status 500 等一些报错，基本可以忽略，重新请求多几次即可

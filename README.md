# iOffice_sqlscan
红帆OA iOffice.net udfmr.asmx处存在SQL注入漏洞。


## 工具利用


python3 sql.py -u http://127.0.0.1:1111 单个url测试

python3 sql.py -f url.txt 批量检测

扫描结束后会在当前目录生成存在漏洞url的vuln.txt

poc：

![](./poc.jpg)

exp：

![](./exp.jpg)

## 免责声明

由于传播、利用此文所提供的信息而造成的任何直接或者间接的后果及损失，均由使用者本人负责，作者不为此承担任何责任。

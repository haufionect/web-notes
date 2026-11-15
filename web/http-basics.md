# Web：HTTP 请求和响应长什么样

```
GET /api/users?page=2 HTTP/1.1
Host: example.com
Accept: application/json

HTTP/1.1 200 OK
Content-Type: application/json

{"users": [...]}
```

- 请求行：方法 + 路径 + 版本；响应行：版本 + 状态码 + 原因。
- 常用方法：GET 查、POST 增、PUT/PATCH 改、DELETE 删。
- 状态码：2xx 成功、3xx 重定向、4xx 客户端错、5xx 服务端错。

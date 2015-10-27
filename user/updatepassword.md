# 修改密码
**JSON请求示例：**
```json
{
    "Token": "3d89386cdf2f92c8b4f3f700262f5537",
    "Params": {
        "password": "",//加密
        "newpassword": ""//加密
    },
    "Method": "updatepassword",
    "Terminal": "1",
    "Version": "2.0",
    "Lat": "100",
    "Lng": "444",
    "UID": "2182534"//必须
}
```
**JSON返回示例：**
```json
{
    "Code": "200",
    "Error": "",
    "Data": "",
    "Token": ""
}
```
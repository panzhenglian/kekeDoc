# 根据邮箱查询用户名
**JSON请求示例**
```json
 {
    "Token": "",
    "Params": {
        "email": "hedeyong666@163.com"
    },
    "Terminal": 3,
    "Version": "2.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 1832536,
    "Method": "customer_getusernamesbyemail"
}
```

**JSON返回示例**
```json
{
    "Code": 200,
    "Msg": "",
    "Error": "",
    "Data": [
        {
            "username": "hedeyong666"
        }
    ],
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
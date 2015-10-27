# 发送邮件验证码
**JSON请求示例：**
```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "email": "hedeyong666@163.com",
        "username":"hedeyong",//注册的时候必须，其他可选
        "flag": "register" // 发送类别标记，有两种 register，forget，bind
    },
    "Terminal": 3,
    "Version": "2.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 1832536,
    "Method": "customer_sendemailcode"
}
```
**JSON返回示例：**
```json
{
    "Code": 200,
    "Msg": "发送成功",
    "Error": "",
    "Data": {},
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
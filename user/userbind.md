# 用户绑定
>**JSON请求示例 有两种**

**1.)邮箱绑定**
```json
{
    "Token": "",
    "Params": {
        "password": "123456",//可选
        "emailcode": "425638", //邮件验证码
        "email": "hedeyong@163.com",//必须
        "flag": "1" // 1代表邮箱，2代表手机 必须
    },
    "Terminal": 3,
    "Version": "2.0",//只有2.0 才有
    "Lat": "100",
    "Lng": "444",
    "Method": "customer_userbind"
}
```


**2.)手机绑定**
```json
{
    "Token": "",
    "Params": {
        "mobile": "13693388010", //手机号 必须
        "mobilecode": "425638", //手机验证码
        "password": "123456",//必须
        "flag": "2" // 1代表邮箱，2代表手机 必须
    },
    "Terminal": 3,
    "Version": "2.0",//只有2.0 才有
    "Lat": "100",
    "Lng": "444",
    "Method": "customer_userbind"
}
```

**JSON返回示例**
```json
{
    "Code": 200,
    "Msg": "绑定成功",
    "Error": "",
    "Data": { },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
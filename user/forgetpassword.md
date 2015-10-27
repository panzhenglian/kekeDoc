# 忘记密码
>**JSON请求示例 有两种**

**1.)邮箱忘记密码**
```json
{
    "Token": "",
    "Params": {
        "password": "123456",//必须
        "emailcode": "425638", //邮件验证码
        "email": "hedeyong@163.com",//必须
        "username": "hedeyong ",//可选 邮箱忘记的时候把用户名传过来
        "flag": "1" // 1代表邮箱注册，2代表手机注册 必须
    },
    "Terminal": 3,
    "Version": "2.0",//只有2.0 才有
    "Lat": "100",
    "Lng": "444",
    "Method": "customer_forgetpassword"
} 
```


**2.)手机忘记密码**
```json
{
    "Token": "",
    "Params": {
        "mobile": "13693388010", //手机号 必须
        "mobilecode": "425638", //手机验证码
        "password": "123456",//必须
        "flag": "2" // 1代表邮箱注册，2代表手机注册 必须
    },
    "Terminal": 3,
    "Version": "2.0",//只有2.0 才有
    "Lat": "100",
    "Lng": "444",
    "Method": "customer_forgetpassword"
}
``` 

**JSON返回示例：**
```json
{
    "Code": 200,
    "Msg": "设置密码成功",
    "Error": "",
    "Data": { },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
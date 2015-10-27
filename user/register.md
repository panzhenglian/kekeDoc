# 注册
> JSON请求示例 有两种

**1.) JSON请求示例（邮箱注册）：**
```json
{
    "Token": "",
    "Params": {
        "username": "hedeyong", //必须
        "password": "123456",//必须
        "email": "hedeyong@163.com",//必须
        "flag": "1" // 1代表邮箱注册，2代表手机注册 必须
    },
    "Terminal": 3,
    "Version": "2.0",//只有2.0 才有
    "Lat": "100",
    "Lng": "444",
    "Method": "customer_register"
}
```


**2.) JSON请求示例（手机注册）：**
```json
{
    "Token": "",
    "Params": {
        "mobile": "13693388010", //手机号 必须
        "mobilecode": "425638", //手机验证码
        "username": "hedeyong", //必须
        "password": "123456",//必须
        "flag": "2" // 1代表邮箱注册，2代表手机注册 必须
    },
    "Terminal": 3,
    "Version": "2.0",//只有2.0 才有
    "Lat": "100",
    "Lng": "444",
    "Method": "customer_register"
} 
```

**JSON返回示例：**
```  
{
    "Code": 200,
    "Msg": "注册成功",
    "Error": "",
    "Data": {
        "uid": 2996361,
        "username": "hedeyong",
        "email": "",
        "icon": "http://uc.kekenet.com/data/avatar/000/00/00/00_avatar_big.jpg",
        "key": "Mfo0LOr7JY/jJ3CbEUc35Q==",
        "iv": "7733332723831738"
    },
    "Token": "1po5gR8X2NR6wyxtfYF/k//jBoAn4S1BwYTlPmZG/64=",
    "IsDecode": 0,
    "Key": ""
}
```
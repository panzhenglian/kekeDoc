# 登陆
>**有三种请求方式**

**1.) 正常登陆JSON请求示例：**
```json
{
    "Lat": "",
    "Lng": "",
    "Method": "login",
    "Params": {
        "username": "WQ6sI2ReGV4ZgCJjFT93Xg==",//加密
        "password": "uL479hh03IgoEsZpoXRr5g==",//加密
        "type": 0 //0 为正常登陆，1 为第三方登陆，2 为游客登陆//int
    },
    "Token": "",
    "UID": "",
    "Version": "2.0",
    "Terminal": 3
}
```

**2.) 第三方 JSON请求示例：**
```json
{
    "Lat": "",
    "Lng": "",
    "Method": "login",
    "Params": {
        "openid": "49327DB6E0AC13045BB81BF28E04D058",
        "accesstoken": "B6226906A38A2B9578D57187A213844A",
        "nickname": "潘正炼",
        "head": "http://q.qlogo.cn/qqapp/100830711/49327DB6E0AC13045BB81BF28E04D058/100",
        "unionid": "",//微信才有
        "opentype": "5",//5为QQ，6为新浪微博，7为微信 //必须//int
        "type": 1//0 为正常登陆，1 为第三方登陆，2 为游客登陆//int
    },
    "Token": "",
    "UID": "",
    "Version": "2.0",
    "Terminal": 3
}
```
**3.) 游客 JSON请求示例：**
```json
{
    "Lat": "",
    "Lng": "",
    "Method": "login",
    "Params": {
        "token": "351670062085472", //token
        "type": 2 //0 为正常登陆，1 为第三方登陆，2 为游客登陆//int

    },
    "Token": "",
    "UID": "",
    "Version": "2.0",
    "Terminal": 3
}
```

**JSON返回示例：**
```json
{
    "Code": 200,
    "Msg": "",
    "Error": 3,
    "Data": {
        "uid": "2958902",
        "username": "keke2958902",
        "email": "",
        "mobile":"136*****010",
        "ispassword":0 ,//代表没有密码，1代表有密码
        "icon": "http://uc.kekenet.com/data/avatar/002/95/89/02_avatar_big.jpg",
        "key": "iZSkXNb1GCfS0Nbr0qGY+w==",//默认密码解密
        "iv": "024af2d02f5d8d72"//扩展
    },
    "Token": "JOHRve43GieBasm4+NreYTJR5ya0HZvmquxUopmIptk=",//用解密后的key 解密token
    "IsDecode": 0,
    "Key": ""//token失效后，返回新的key  和token 
}
```
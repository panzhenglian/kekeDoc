# 发送短信
**JSON请求示例：**
```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "mobile": "13693388010",
         "username":"hedeyong",//注册的时候必须，其他可选
         "flag": "register" // 发送类别标记，有两种 register，forget，bind
		 "isnew":1//新版本注册时添加，不用传递用户名
    },
    "Terminal": 3,
    "Version": "1.0",//1.0 ，2.0 都是一样
    "Lat": "100",
    "Lng": "444",
    "UID": 1832536,
    "Method": "customer_sendmsg"
}
```

> 备注：除了注册和忘记密码外，绑定手机需要传uid 和 token 
> 新版本注册 

**JSON返回示例：**  
```json
{
    "Code": 200,
    "Msg": "发送成功",
    "Error": "",
    "Data": {
        "status": 1 //1代表发送成功，0或者-1 代表失败
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
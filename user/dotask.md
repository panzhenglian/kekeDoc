# 每日任务
>**目前有3种任务请求** 
   
**1. 告诉朋友，JSON请求示例：**
```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "type": 1,// 1 表示告诉朋友，2 表示分享内容 ，3 表示内容收听
        "sharetype": 1 // 告诉好友类型 1 表示朋友圈，2 qq空间，3新浪微博 ，4 qq， 5 微信
    },
    "Method": "customer_dotask",
    "Terminal": 3,
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 49
}
```
**2. 分享内容，JSON请求示例：**
```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "type": 2// 1 表示告诉朋友，2 表示分享内容 ，3 表示内容收听
    },
    "Method": "customer_dotask",
    "Terminal": 3,
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 49
}
```

**3. 收听人物，JSON请求示例：**
```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "type": 3,
        "time": 1436000429,
        "minute": 10
    },
    "Method": "customer_dotask",
    "Terminal": 3,
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 49
}
```
**JSON返回示例：**
```json
{
    "Code": 200,
    "Error": "",
    "Data": {
        "uid": 49,
        "date": 1436089592,
        "num": 40//积累的分钟数或打卡次数
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```

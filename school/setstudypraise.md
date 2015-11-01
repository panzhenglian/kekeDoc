# 设置学堂点赞
**JSON请求示例：**
 
```json
{
    "Method": " v9_news_setstudypraise",
    "UID": "2793192",
    "Version": "2.0",
    "Lat": "",
    "Lng": "",
    "Params": {
        "userid": 2793192,// 用户id 
        "searchtype": 0 // 0听力，1 口语
    },
    "Token": "4EB5AE049AC0FA719B5D4843B953C784",
    "Terminal": 3
}
```

**JSON返回示例：**
 
```json
{
    "Code": 200,
    "Msg": "",
    "Error": "",
     "Data": {
        "status": 1 //1 成功，0 失败，2 已经添加
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
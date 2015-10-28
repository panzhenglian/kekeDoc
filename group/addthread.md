# 添加话题
**JSON 请求示例：**
```json
{
    "Token": "",
    "Params": {
        "tagid": 18,
        "subject": "相信自己就能成功",
        "msg": "发动机"
    },
    "Method": "thread_addthread",
    "Terminal": "1",
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 310861
}
``` 
**JSON返回示例：**
```json
{
    "Code": 200,
    "Error": "",
    "Data": {
        "tid": 400661, // 话题列表id
        "pid": 562013 // 主题id
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
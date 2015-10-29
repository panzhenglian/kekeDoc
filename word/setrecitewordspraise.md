# 背单词点赞
**JSON 请求示例：**
```json
{
    "Method": "word_setrecitewordspraise",
    "UID": "2793192",
    "Version": "2.0",
    "Lat": "",
    "Lng": "",
    "Params": {
        "userid": 2793192 //被点赞的人
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
        "status": 1 //0 代表失败，1代表成功，2代表已经点赞
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
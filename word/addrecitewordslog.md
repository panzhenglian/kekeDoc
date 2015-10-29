# 添加背诵日志
`注意：Params  加密`
**JSON 请求示例：**
```json
{
    "Method": "word_addrecitewordslog",
    "UID": "2793192",
    "Version": "2.0",
    "Lat": "",
    "Lng": "",
    "Params": {
        "wordcount": 12, //单词数
        "credit": 12,//积分
        "minute": 12,//分钟
        "levelcount": 1//关数,
        "dateline":11111,//时间（）
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
        "status": 1 //0 代表失败，1代表成功
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
# 删除私信
**JSON 请求示例：**
```json
{
    "Token": "",
    "Params": {
        "mids": "41,42"
    },
    "Terminal": "0",
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "Method": "msg_deletemsgs",
    "UID":49
}
``` 
**JSON返回示例：**
```json
{
    "Code": "200",
    "Msg": "",
    "Data": [
        {
            "mid": "41",
            "uid": "7290",
            "result": 1
        },
        {
            "mid": "42",
            "uid": "7290",
            "result": 1
        }
    ],
    "Token": ""
}
```
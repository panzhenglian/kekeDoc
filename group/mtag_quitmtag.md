# 退出小组
**JSON 请求示例：**
```json
{
    "Token": "",
    "Params": {
        "tagid": 18
    },
    "Method": "mtag_quitmtag",
    "Terminal": "1",
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 2189325
}
```
**JSON返回示例：**
```json
{
    "Code": 200,
    "Error": "",
    "Data": {
        "status": "3"//0 退出失败，1退出成功
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
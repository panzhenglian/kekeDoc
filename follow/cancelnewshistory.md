# 取消文章浏览记录
**JSON请求示例：**

```json
{
    "Lat": "",
    "Lng": "",
    "Method": "favorites_cancelnewshistory",
    "Params":
    {
        " articleids": "14614|15213"
    },
    "Token": "DBFFE1CA2718367296CE6EB8AD583BC8",
    "UID": "2929415",
    "Version": "1.0",
    "Terminal": 3
}
```
**JSON返回示例：**

```json
{
    "Code": 200,
    "Msg": "",
    "Error": "",
    "Data": [
        {
            "articleid": "14614",
            "status": 0 // 0 未成功，1成功
        },
        {
            "articleid": "15213",
            "status": 0
        }
    ],
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
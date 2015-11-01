# 添加节目收藏
**JSON请求示例：**

```json 
{
    "Lat": "",
    "Lng": "",
    "Method": "favorites_addmenu",
    "Params":
    {
        "catids": "14614|15213"
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
            "catid": 14614,
            "status": 2 //0 失败，1 成功，2 已收藏
        },
        {
            "catid": 15213,
            "status": 2
        }
    ],
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
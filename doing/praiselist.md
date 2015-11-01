# 动态点赞列表
**JSON 请求示例：**

```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "doid": 400288,
        "PageIndex": 1,
        "PageSize": 20
    },
    "Terminal": 3,
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 163898,
    "Method": "doing_praiselist"
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
            "username": "kekenet",
            "icon": "http://uc.kekenet.com/data/avatar/000/16/38/98_avatar_middle.jpg",
            "uid": "163898"
        }
    ],
    "Token": "",
    "PageIndex": 1,
    "PageSize": 20,
    "PageCount": 1,
    "IsDecode": 0,
    "Key": ""
}
```
# 节目收藏列表
**JSON请求示例：**

```json
{
    "Lat": "",
    "Lng": "",
    "Method": "favorites_menulist",
    "Params":
    {
        "PageIndex": 1,
        "PageSize": 1

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
            "catid": "15822", //节目id
            "lmpic": "http://pic.kekenet.com/column/201508/1440581289.jpg",//缩略图
            "catname": "美国探索频道:恐龙之战",//节目名称
            "num": "574" //文章数
        }
    ],
    "Token": "",
    "PageIndex": 1,
    "PageSize": 1,
    "PageCount": 26,
    "IsDecode": 0,
    "Key": ""
}
```
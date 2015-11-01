# 获取测试过的句子
**JSON请求示例：**

```json
{
    "Method": "v9_news_getstudysentence",
    "UID": "2793192",
    "Version": "2.0",
    "Lat": "",
    "Lng": "",
    "Params": {
        "catid":11,
        "id": 379492,
        "searchtype": 0
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
        "result": {
            "ranking": 11,
            "credit": "2",
            "successrate": "60%",
            "nextid":1
        },
        "list": [
            {
                "en": "BBC News with Joe Mocintosh.",
                "cn": "乔·麦金塔什为你播报BBC新闻。",
                "credit": "1"
            },
            {
                "en": "A40-pagedossierhasbeenreleasedbytheUSJusticeDepartment",
                "cn": "美国司法部公布了一份40页的文件，",
                "credit": "1"
            }
        ]
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
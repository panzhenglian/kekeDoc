# 获取学堂等级
**JSON请求示例：**

```json
{
    "Token": "fe95d19f1d8ccf8e4a2f5681b91dc87c",
    "Params": {
       "searchkey":1
    },
    "Method": "v9_news_getclasslevel",
    "Terminal": "2",
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": "202921"
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
            "level": 1,
            "title": "日常英语"
        },
        {
            "level": 2,
            "title": "职场英语"
        },
        {
            "level": 3,
            "title": "旅行英语"
        },
        {
            "level": 4,
            "title": "影音娱乐"
        },
        {
            "level": 5,
            "title": "商务口语"
        },
        {
            "level": 6,
            "title": "行业口语"
        },
        {
            "level": 7,
            "title": "法律金融"
        },
        {
            "level": 8,
            "title": "少儿口语"
        },
        {
            "level": 9,
            "title": "经典教材"
        }
    ],
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
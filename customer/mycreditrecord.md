# 我的积分纪录
**JSON请求示例：**
```json
{
    "Token": "fe95d19f1d8ccf8e4a2f5681b91dc87c",
    "Params": {
       "PageIndex": 1,
       "PageSize": 10,

    },
    "Method": "customer_mycreditrecord",
    "Terminal": "2",
    "Version": "2.0",
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
            "total": 0,
            "title": "签到",
            "dateline": "2015-09-24",
            "credits": "20"
        },
        {
            "total": 0,
            "title": "签到",
            "dateline": "2015-09-23",
            "credits": "20"
        },
        {
            "total": 0,
            "title": "收听",
            "dateline": "2015-09-22",
            "credits": "18"
        }
    ],
    "Token": "",
    "PageIndex": 0,
    "PageSize": 3,
    "PageCount": 8,
    "IsDecode": 0,
    "Key": ""
}
```
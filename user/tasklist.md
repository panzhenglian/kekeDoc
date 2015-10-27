# 任务列表
**JSON请求示例：**
```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params":“”,//没有参数
    "Method": "customer_tasklist",
    "Terminal": 3,
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 49
}
```


**JSON返回示例：**
```json
{
    "Code": 200,
    "Error": "",
    "Data": {
    "userinfo": {
            "totalpoint": "1118",
            "username": "admin",
            "icon": "http://uc.kekenet.com/data/avatar/000/00/00/49_avatar_middle.jpg",
            "uid": 49
        },
        "sign": {
            "num": 4,
            "todayflag": 0 //0 代表没有，1 代表有
        },
        "tasklist": [
            {
                "num": 0,
                "title": "告诉朋友(0/4)",
                "description": "每日分享到微信或者朋友圈就能获取到50-100可可豆",
                "max": 4,
                "type": 1
            },
            {
                "num": 0,
                "title": "内容分享(0/4)",
                "description": "内容分享，每日能获取到500可可豆",
                "max": 4,
                "type": 2
            },
            {
                "num": 0,
                "title": "内容收听0/100)",
                "description": "每日收听，可以获取的100可可豆",
                "max": 100,
                "type": 3
            }
        ]
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
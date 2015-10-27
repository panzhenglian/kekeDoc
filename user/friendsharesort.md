# 好友推荐排序
**JSON请求示例：**
```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {},//没有参数
    "Method": "customer_friendsharesort",
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
        "myshare": {//登陆用户积累打卡数量
            "total": 1,
            "month": 1,
            "uid": 49，
            "username": "bluewhite",
            "icon": "http://uc.kekenet.com/data/avatar/000/00/00/49_avatar_middle.jpg"
        },
        "SortList": [ //打卡排序列表
            {
                "total": "1",
                "month": 1,
                "uid": 1，
                "username": "bluewhite",
                "icon": "http://uc.kekenet.com/data/avatar/000/00/00/49_avatar_middle.jpg"
            }
        ]
    },
    "Token": "",
    "PageIndex": 1,
    "PageSize": 10,
    "PageCount": 1,
    "IsDecode": 0,
    "Key": ""
}
```
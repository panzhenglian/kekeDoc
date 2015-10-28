# 获取话题信息
**JSON 请求示例：**
```json
   {
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "tid": 400608
    },
    "Method": "thread_threadmsg",
    "Terminal": 3,
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
        "tagid": "1233",
        "tagname": "每日名言",
        "tid": 403141,
        "subject": "【每日名言】20150720期:May there be enough clouds",
        "viewnum": "16",
        "replynum": "10",
        "flower": "1",
        "isclick": 0,
        "ispost": 0,
        "icon": "http://uc.kekenet.com/data/avatar/001/83/25/36_avatar_middle.jpg",
        "dateline": "1437354252",
        "username": "tyswy",
        "pf": "",
        "isjoin":0,
        "mp3": "2015/07/20/56269626.mp3",
        "uid": "1832536",
        "message": "May there be enough clouds in your life to make a beautiful sunset.</b>\n参考译文：</b>\n愿你生命中有够多的云翳，来造成一个美丽的黄昏。\n小编：</b>\n青春，从来都是一场不缺磨难的旅途。成长，就是逼着你一个人，踉踉跄跄的受伤，跌跌撞撞的坚强。时间流逝，从此你也变得不一样。"
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
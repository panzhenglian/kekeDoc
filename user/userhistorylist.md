# 获取用户浏览记录列表
**JSON请求示例：**
```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "userid": 163898
    },
    "Terminal": 3,
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 2284607,
    "Method": "customer_userhistorylist"
}
```

**JSON返回示例： 默认100**
```json
 {
    "Code": 200,
    "Error": "",
    "Data": [
        {
            "news_id": "374475",
            "time": "2015-05-12 12:43:15",
            "updatetime": 1431405795,
            "title": "欧美人文风情(视频+文本+字幕)第109篇:美国国债你我他",
            "thumb": "http://pic.kekenet.com//2015/0512/98031431402064.png", //背景图
            "download": "Sound/2015/05/oumei123_3634762tbJ.mp3",//音频地址
            "catid": "15287",//类别id
            "type": 3
        },
        {
            "news_id": "373637",
            "time": "2015-05-12 12:26:44",
            "updatetime": 1431404804,
            "title": "高三英语分模块视频课堂 Module1 Unit1:reaching out(3)",
            "thumb": "",
            "download": "http://player.youku.com/player.php/sid/XNzM0MzU2MjIw/v.swf",
            "catid": "15613",
            "type": 1
        },
        {
            "news_id": "374110",
            "time": "2015-05-12 11:23:27",
            "updatetime": 1431401007,
            "title": "每日视频新闻:老外品尝上海本地小吃",
            "thumb": "http://pic.kekenet.com/2015/0509/1431125738.jpg",
            "download": "",
            "catid": "13403",
            "type": 1
        }
    ],
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
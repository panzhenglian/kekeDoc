# 获取最新节目**多个**(全部-听-说-读)的全部}
**JSON请求示例：**
```json
{
    "Token": "",
    "Params": [
        {
            "catid": 11012,
            "count": 1
        },
        {
            "catid": 13462,
            "count": 1
        }
    ],
    "Method": "v9_news_newcolumnlists",
    "Terminal": 3,
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 379899
}
```

**JSON返回示例：**
```json
 {
    "Code": 200,
    "Error": "",
    "Data": [
        {
            "channel": "双语阅读",
            "catid": 11012,
            "list": [
                {
                    "catname": "蒋健棠教你听英语广播",
                    "catid": "895",
                    "lmpic": "http://pic.kekenet.com/column/201505/1430721887.jpg",
                    "rank": "0",
                    "title": "十位农民出身的统治者(3)",
                    "type": 1,
                    "updatetime": "2015-07-17",
                    "thumb": "http://pic.kekenet.com//2015/0716/45451437041328.jpg",
                    "news_id": "386089"
                },
                {
                    "catname": "蒋健棠教你听英语广播",
                    "catid": "2053",
                    "lmpic": "http://pic.kekenet.com/column/201411/1416321698.jpg",
                    "rank": "0",
                    "title": "创建不同凡响公司名的15个王牌标准",
                    "type": 1,
                    "updatetime": "2015-07-17",
                    "thumb": "http://pic.kekenet.com//2015/0716/51191437040129.png",
                    "news_id": "386079"
                },
                {
                    "catname": "蒋健棠教你听英语广播",
                    "catid": "2428",
                    "lmpic": "http://pic.kekenet.com/column/201411/1416321364.jpg",
                    "rank": "0",
                    "title": "美食专家:用餐必知的十个好习惯(2)",
                    "type": 1,
                    "updatetime": "2015-07-16",
                    "thumb": "http://pic.kekenet.com//2015/0716/671437034822.jpg",
                    "news_id": "386048"
                }
            ]
        },
        {
            "channel": "英语听力",
            "catid": 10001,
            "list": [
                {
                    "catname": "蒋健棠教你听英语广播",
                    "catid": "13979",
                    "lmpic": "http://pic.kekenet.com/column/201502/1423984887.jpg",
                    "rank": "0",
                    "title": "可可Radio第935期:拒绝快餐-快餐会使人上瘾(2)",
                    "type": 2,
                    "download": "Sound/2015/07/20150710_07079297ei.mp3",
                    "updatetime": "2015-07-16",
                    "thumb": "http://pic.kekenet.com//2015/0716/70371437056890.jpg",
                    "news_id": "386109"
                },
                {
                    "catname": "蒋健棠教你听英语广播",
                    "catid": "15463",
                    "lmpic": "http://pic.kekenet.com/column/201501/1421979057.jpg",
                    "rank": "0",
                    "title": "美国学生世界地理教材(MP3+中英字幕) 第59期:之最最多的西部续(1)",
                    "type": 3,
                    "download": "Sound/2015/07/dili16a1.mp3",
                    "updatetime": "2015-07-16",
                    "thumb": "",
                    "news_id": "386088"
                },
                {
                    "catname": "蒋健棠教你听英语广播",
                    "catid": "14117",
                    "lmpic": "http://pic.kekenet.com/column/201410/1414419932.jpg",
                    "rank": "0",
                    "title": "BBC地平线系列之《你喝多了吗》第21集:30年的酒精毒",
                    "type": 3,
                    "download": "Sound/2015/07/bbc21.mp3",
                    "updatetime": "2015-07-16",
                    "thumb": "",
                    "news_id": "384811"
                }
            ]
        }
    ],
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
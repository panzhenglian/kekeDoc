# 文章列表
**JSON请求示例：**
```json
{
    "Token": "fe95d19f1d8ccf8e4a2f5681b91dc87c",//必须
    "Params": {
        "catid": "124",
        "PageIndex": 1,
        "PageSize": 20,
        "Sort":"inputtime desc", //可选 格式:属性+排序方式, 如：inputtime desc 倒序 相反 inputtime asc
    },
    "Method": "v9_news_getnewslist",
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
    "Error": "",
    "Data": {
        "lmname": "在线广播",
        "channel": "BBC News",
        "video": "0",
        "ting": "1",
        "book": "0",
        "url": "http://m.kekenet.com/broadcast/BBC/",
        "rank": "4",
        "lmpic": "http://pic.kekenet.com/column/201501/1422696913.jpg",
        "intro": "可可英语为您提供从2008年3月到现在每天的BBC News,内容包括BBC在线收听、BBC听力下载、中英字幕、中文翻译、长难句讲解，同时可进行BBC听写训练，帮你练习听力，丰富词汇，全面提高英语水平。\n",
        "guanzhu": "5178",
        "num": "3920",
        "hits": 3.25,
        "rowcount": "3920", 
        "list": [
            {
                "id": "379492",
                "thumb": "",
                "title": "BBC双语新闻讲解附字幕:国际足联前官员布莱泽详述受贿案",
                "download": "Sound/2015/06/bbc0609_1044324hWe.mp3",
                "lrc": "",
                "type": 2,
                "switch": 0,
                "updatetime": "2015-06-09",
                "hits": "26",
                "mp3size": 0,
                "mp3byte": "0",
                "mp3len": ""
            } 
        ]
    },
    "Token": "",
    "PageIndex": 1,
    "PageSize": 20,
    "PageCount": 197,
    "IsDecode": 0
}
```
# 获取课程章节列表
**JSON请求示例：**

```json
{
    "Token": "fe95d19f1d8ccf8e4a2f5681b91dc87c",
    "Params": {
        "catid": "124",
        "PageIndex": 1,
        "PageSize": 1,
        "Sort":"inputtime desc"
    },
    "Method": "v9_news_getchapterlist",
    "Terminal": "3",
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
    "Data": {
        "lmname": "在线广播", 
        "channel": "BBC News",//课程名称（渠道名称）
        "rowcount": "4027",//文章数
        "video": "0",
        "ting": "1",//是否为听，//1 听，0不是
        "book": "0",//是否是系列 //0不是，1 是
        "url": "http://m.kekenet.com/broadcast/BBC/",
        "rank": "4",
        "lmpic": "http://pic.kekenet.com/column/201501/1422696913.jpg",//缩略图
        "intro": "可可英语为您提供从2008年3月到现在每天的BBC News,内容包括BBC在线收听、BBC听力下载、中英字幕、中文翻译、长难句讲解，同时可进行BBC听写训练，帮你练习听力，丰富词汇，全面提高英语水平。\n",//描述
        "guanzhu": "10449",//关注度
        "num": "4026",
        "hits": 21.13,//点击率 （万为单位）
        "list": [
            {
                "id": "399349",//文章id
                "thumb": "http://pic.kekenet.com//2015/0917/93031442473646.jpg",//缩略图
                "title": "朝鲜全面重启宁边主要核设施",//标题
                "download": "Sound/2015/09/bbc20150917_0532817RpV.mp3",//音频地址
                "lrc": "Sound/2015/09/4ab71b519712fd1c6a18.lrc",//生词本
                "type": 3,
                "switch": 0,
                "updatetime": "2015-09-17",//更新时间
                "hits": 2404,//点击率
                "mp3size": 0,
                "mp3byte": "0",
                "mp3len": "",
                "catid": "15499",//课程id
                "peoplecount": "0"//多少人学习
            } 
        ]
    },
    "Token": "",
    "PageIndex": "1",
    "PageSize": "20",
    "PageCount": 202,
    "IsDecode": 0,
    "Key": ""
}
```
# 我的学堂训练
>有三种请求 JSON请求示例 ：

**1.0 我的课程JSON请求示例：**

```json
{
    "Method": "v9_news_getstudymsg",
    "UID": "2793192",
    "Version": "2.0",
    "Lat": "",
    "Lng": "",
    "Params": {
        "studytype": 0,// 0 我的课程，1 已经完成，2 排行
        "searchtype": 0, // 0听力，1 口语
        "sorttype":1 //排序类型 //0 代表昨天，1代表本周，2代表本月，3代表总的//默认为1本周
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
    "Data": [
        {
            "is_book": "0",//是否系列 //扩展
            "rank": "2",//扩展
            "catid": "96",//课程id
            "catname": "VOA慢速英语", //名称
            "guanzhu": "15010",//关注数
            "lmpic": "http://pic.kekenet.com/column/201412/1417599842.jpg",//缩略图
            "num": "6619",//文章数量
            "updatetime": "2015-09-15",//更新时间
            "close": "1",//是否关闭 
            "ting": "1",//扩展
            "type": 1,//扩展
            "topid": null,//扩展
            "topname": "在线广播",//扩展
            "finishcount": "0"//完成数量
        }
    ],
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
**2.0  已经完成 文章列表 JSON请求示例：**

```json
{
    "Method": "v9_news_getstudymsg",
    "UID": "2793192",
    "Version": "2.0",
    "Lat": "",
    "Lng": "",
    "Params": {
        "studytype": 1,// 0 我的课程，1 已经完成，2 排行
        "searchtype": 0, // 0听力，1 口语
        "sorttype":1, //排序类型 //0 代表昨天，1代表本周，2代表本月，3代表总的//默认为1本周
        "PageIndex": 1,
        "PageSize": 20

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
        "mystudylog": { //我的学习日志
            "studycount": 0,//学习总的文章数
            "minutes": 0,//总的学习时间
            "credits": 0,//总积分
            "praisecount": 0 //点赞
        },
       "list": [
            {
                "title": "", //标题
                "peoplecount": 0,//学习人数
                "news_id": 0,//文章id
                "dateline": 0， //学习的时间
                 "credit":0 //得分
            }
        ]
    },
    "Token": "",
    "PageIndex": 1,
    "PageSize": 15,
    "PageCount": 0,
    "IsDecode": 0,
    "Key": ""
}
```

**3.0   排行榜 JSON请求示例：**

```json
{
    "Method": "v9_news_getstudymsg",
    "UID": "2793192",
    "Version": "2.0",
    "Lat": "",
    "Lng": "",
    "Params": {
        "studytype": 2,// 0 我的课程，1 已经完成，2 排行
        "searchtype": 0, // 0听力，1 口语
        "sorttype":1, //排序类型 //0 代表昨天，1代表本周，2代表本月，3代表总的//默认为1本周
        "PageIndex": 1,
        "PageSize": 20

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
        "pageCount": 0,
        "list": [
            {
                "studycount": 0,// 学习的数量
                "minutes": 0,//总的分钟数
                "credits": 0,//积分
                "praisecount": 0,//点赞数
                "icon": "",//头像
                "username": ""//用户名
                "uid":12
            }
           ],
        "mystudylog": {
            "studycount": 0,
            "minutes": 0,
            "credits": 0,
            "praisecount": 0,
            "icon": "http://uc.kekenet.com/data/avatar/002/79/31/92_avatar_middle.jpg",
            "username": "keke2793192",
         "ispraised": 1
        }
    },
    "Token": "",
    "PageIndex": 0,
    "PageSize": 0,
    "PageCount": 0,
    "IsDecode": 0,
    "Key": ""
}
```
# 背诵排序
**JSON 请求示例：**
```json
{
    "Method": "word_recitewordssort",
    "UID": "2793192",
    "Version": "1.0",
    "Lat": "",
    "Lng": "",
    "Params": {
        "PageIndex": 1,
        "PageSize": 20,
        "searchtype": 0,//0代表积分排行，1代表关数（扩展）
        "sorttype": 1 //0 是昨天排序，1是本周排序，2是本月排序，3是总
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
        "list": [
            {
                "wordcount": "12",//单词总数
                "minutes": "12",//分钟总数
                "credits": "12",//积分总数
                "praisecount": "1",//点赞总数
                "levelcount": "1",//关卡总数
                "icon": "http://uc.kekenet.com/data/avatar/002/79/31/92_avatar_middle.jpg",//头像
                "username": "keke2793192",//用户名
                "uid": "2793192",//用户id
                "ispraised": 1//是否点赞 0 没有，1已经点赞
            }
        ],
        "myrecitelog": { //我的背诵日志
                "wordcount": "12",//单词总数
                "minutes": "12",//分钟总数
                "credits": "12",//积分总数
                "praisecount": "1",//点赞总数
                "levelcount": "1",//关卡总数
                "icon": "http://uc.kekenet.com/data/avatar/002/79/31/92_avatar_middle.jpg",//头像
                "username": "keke2793192",//用户名
                "uid": "2793192",//用户id
                "ispraised": 1//是否点赞 0 没有，1已经点赞
        }
    },
    "Token": "",
    "PageIndex": 1,
    "PageSize": 20,
    "PageCount": 1,
    "IsDecode": 0,
    "Key": ""
}
```
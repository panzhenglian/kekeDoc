# 获取我的小组更多
**JSON 请求示例：**
```json
{
    "Token": "3d89386cdf2f92c8b4f3f700262f5537",
    "Params": {},
    "Method": "thread_myteammore",
    "Terminal": "1",
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 2182534
}
```
**JSON返回示例：**
```json
{
    "Code": 200,
    "Error": "",
    "Data": [
        {
            "tagid": "1200",//组id
            "tagname": "每日一句",//组名
            "threadsubject": "hhhh",//帖子标题
            "threadtime": "1437472037",//时间
             " announcement":"反反复复",//
            "pic": "http://dipan.kekenet.com/attachment/group/2015/dailyju.jpg",//背景图
            "membernum": "14",//人气
            "postnum": "81",//帖子数
            "isjoin": "1",//0 表示未加入，1表示已经加入
            "isopen":0 //是否开放（是否允许发帖子）
        },
        {
            "tagid": "470",
            "tagname": "经典英文歌曲",
            "threadsubject": "Dark Of Night 走出黑暗，又一个精彩的你~",
            "threadtime": "1437458847",
            "pic": "http://dipan.kekenet.com/attachment/group/2015/jingdiansong.jpg",
            "membernum": "10270",
            "postnum": "21768",
            "isjoin": "1",
            "isopen":0 //是否开放（是否允许发帖子）
        }
    ],
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
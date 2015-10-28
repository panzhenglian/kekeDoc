# 获取推荐小组信息
**JSON 请求示例：**
```json
{
    "Token": "3d89386cdf2f92c8b4f3f700262f5537",
    "Params": {
        "type": 1，//1 代表hotgroup，2代表daily，3代表 english，4 代表 movie，//也可以直接传类别名称 如：hotgroup
    },
    "Method": "thread_recommendmtag",
    "Terminal": "1",
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 62
}
```
**JSON返回示例：**
```json
{
    "Code": 200,
    "Error": "",
    "Data": [
        {
            "tagid": "1200",
            "tagname": "每日一句",
            "announcement": "",
            "pic": "",
            "membernum": "2",
            "postnum": "92",
            "isjoin": "0",
          "isopen":0 //是否开放（是否允许发帖子）
        },
        {
            "tagid": "470",
            "tagname": "经典英文歌曲",
            "announcement": "群组公告：【我猜我猜我猜猜猜】Afternoon Coffee Hour音乐擂台赛结束！\r\n欢迎您继续与大家分享好听的英文歌曲~~~",
            "pic": "http://dipan.kekenet.com/attachment/group/2015/jingdiansong.jpg",
            "membernum": "10248",//人气
            "postnum": "21673", //帖子 数
            "isjoin": "0",//是否加入，0未加入，1 为加入
            "isopen":0 //是否开放（是否允许发帖子）
        }
    ],
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
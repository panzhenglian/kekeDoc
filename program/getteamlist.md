# 节目推荐小组
**JSON请求示例：**
```json
{
    "Token": "bd6c476550a0ef99526645961f2e6d1e",
    "Params": {
        "catid": "1563" //节目id
    },
    "Method": "v9_news_ getteamlist",
    "Terminal": 3,
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 2929415
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
            "tagid": "470",//小组id
            "tagname": "经典英文歌曲",//小组名称
            "announcement": "群组公告：【我猜我猜我猜猜猜】Afternoon Coffee Hour音乐擂台赛结束！ \r\n欢迎您继续与大家分享好听的英文歌曲~~~",//公告
            "pic": "http://dipan.kekenet.com/attachment/group/2015/jingdiansong.jpg",//背景图
            "membernum": "10279",//人气
            "postnum": "22086",//列子数
            "isjoin": "0" //是否加入 //0 表示未加入，1表示已加入
        },
        {
            "tagid": "947",
            "tagname": "每日短语",
            "announcement": "【每日短语听写小组】每天一句英语短语, 听力提高没有问题!",
            "pic": "http://dipan.kekenet.com/attachment/group/2015/dailyduanyu.jpg",
            "membernum": "268",
            "postnum": "1565",
            "isjoin": "0"
        },
        {
            "tagid": "1200",
            "tagname": "每日一句",
            "announcement": "每日推送一句，可进行跟读模仿，系统自动打分",
            "pic": "http://dipan.kekenet.com/attachment/group/2015/dailyju.jpg",
            "membernum": "18",
            "postnum": "1794",
            "isjoin": "0"
        }
    ],
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
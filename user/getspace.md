# 获取个人主页
**请求参数：**  

| 名称      |    类型 | 是否必填写  | 说明 |
| :-------- | :-------- | :--------| :--------  |
| userid  | int |  是   | 用户id

**JSON请求示例：**  
```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "userid": 379492
    },
    "Method": "customer_getspace",
    "Terminal": 3,
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 49
}
```
**JSON返回示例：**
```json
{
    "Code": 200,
    "Error": "",
    "Data": {
        "userinfo": {
           "username": "bluewhite",// 用户名
            "icon": "http://uc.kekenet.com/data/avatar/000/00/00/49_avatar_middle.jpg",
            "fansnum": "1",//粉丝数量
            "totalpoint":"100",//总积分(可可豆)
            "singnum": 1,//连续签到数量
            "listennum": "10",//收听分钟数
            "mp3len": 0,//录音数量
            "attentionnum": "1",//关注数量
	        "teamnum": "1",//小组数
	        "doingcount": "1",//动态数
            "levelinfo": {
                "level": 1,//等级数
                "title": "初级可友" //等级名称
             },
             "subscription": "1",//订阅数
             "attentionflag": 0// -1表示未关注 ,0 表示单关注，1 表示相互关注，2表示取消关注,3 表示被取消关注
        },
        "subscription": {
            "count": "52",//总数
            "list": [//订阅列表 默认4个
                {
            			"catid": "15328",//类别id
            			"lmpic": "http://pic.kekenet.com/column/201411/1417095027.jpg",//图片
            			"catname": "英语六级分类阅读训练附解析",//类别名称
            			"num": "2033" //订阅量
                } 
            ]
        },
        "mytingrecord": {
            "count": "2",//总数
            "list": [//九宫格听写 列表
                {
                    "news_id": "368387",//文章id
                "title": "纪录片《鲸奇之旅Ocean Voyagers》(MP3+中英字幕) 第13期:鲸奇之旅(2)",
                "score": "15",//得分 
                "time": "37566",//耗时
                "updatetime": "2015-04-10", //时间
                "catid": "15528",//类型id
                "catname": "纪录片《鲸奇之旅Ocean Voyagers》",//类别名称
                "type": 3 //文章内容类型 1 文本 3 为音频
                }
            ]
        },
        "history": {
            "count": "7380", // 总数
            "list": [//浏览历史记录 列表
                {
                   "news_id": "374579",//文章id
                "time": "2015-05-12 18:13:55",
                "updatetime": "2015-05-12 18:13:55",
                "title": "甜蜜清新英文歌曲(MP3+双语歌词) 第20期:Enchanted",
                "thumb": "",//缩略图
                "download": "Sound/2015/05/safmusic24_0018514jwn.mp3",// 播放地址
                "catid": "15523",//类型id
                "type": 3//文章内容类型 1 文本 3 为音频
                } 
            ]
        }
         
    },
    "myteam": { //我的小组
            "count": "5", //总数
            "list": [
                {
                    "tagid": "302", //组id
                    "tagname": "每日学口语", //组名
                    "announcement": "每日一句，日积月累，练习口语",//公告
                    "pic": "http://dipan.kekenet.com/attachment/group/2015/didaokouyu.jpg",//背景图
                    "membernum": "5626",//人气
                    "postnum": "20658",//帖子数
                    "isjoin": "1" //是否加入状态 0 表示未加入，1 表示已经加入
                },
                {
                    "tagid": "947",
                    "tagname": "每日短语",
                    "announcement": "【每日短语听写小组】每天一句英语短语, 听力提高没有问题!",
                    "pic": "http://dipan.kekenet.com/attachment/group/2015/dailyduanyu.jpg",
                    "membernum": "266",
                    "postnum": "704",
                    "isjoin": "1"
                },
                {
                    "tagid": "865",
                    "tagname": "每日翻译",
                    "announcement": "本群组专为喜欢翻译以及希望通过翻译来提高英语运用能力的朋友建立，欢迎各位来此发布翻译信息以及回复内容，在交流中提高翻译能力。翻译是一种提高英语能力的有效办法，希望译群组能给各位带来帮助和乐趣。",
                    "pic": "http://dipan.kekenet.com/attachment/group/2015/dailyfanyi.jpg",
                    "membernum": "3100",
                    "postnum": "19239",
                    "isjoin": "1"
                }
            ]
        }
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}

```

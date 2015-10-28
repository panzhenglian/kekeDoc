# 获取我的小组
**JSON 请求示例：**
```json
{
    "Token": "3d89386cdf2f92c8b4f3f700262f5537",
    "Params": {
    },
    "Method": "thread_myteam",
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
    "Data": {
        " latestdynamicnum ":122,//最新动态数
        "myteamlist": [
            {
                "tagid": "1200", //组id
                "tagname": "每日一句",//组名称
                "threadsubject": "hhhh",//最新帖子的标题
                "threadtime": "1437472037",//发帖时间
                "pic": "http://dipan.kekenet.com/attachment/group/2015/dailyju.jpg",//背景图
                "membernum": "14",//人气
                "postnum": "81",//帖子数
                "isjoin": "1" ,//是否加入
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
                "isjoin": "1"，
	         "isopen":0 //是否开放（是否允许发帖子）
            }
        ],
        "hotgrouplist": [
            {
                "tagid": "302", //组id
                "tagname": "每日学口语",//组名
                "announcement": "每日一句，日积月累，练习口语",//说明
                "pic": "http://dipan.kekenet.com/attachment/group/2015/didaokouyu.jpg",//背景图
                "membernum": "5623",//人气
                "postnum": "20635",//帖子数
                "isjoin": "0" //0 代表未加入，1代表已加入
              "isopen":0 //是否开放（是否允许发帖子）
            },
            {
                "tagid": "802",
                "tagname": "可可地盘听写竞赛",
                "announcement": "★将学习英语坚持到底★ \r\n★邀请志同道合的朋友加入到我们的听写队伍。 \r\n★目前听写竞赛分为 \r\n 【可可地盘短句听写擂台赛】-初级； \r\n【可可地盘听写擂台赛】-中级；每周一、三、五晚上更新哦~ \r\n 可可地盘听写挑战赛】-高级。 \r\n 【可可地盘歌词听写擂台赛】-混合级。 \r\n ★10次获得听写王称号的朋友将成为群组的明星成员。 \r\n ★提交听写答案时，请用“回复只有楼主可见” \r\n=============================== \r\n ★现场听写版★ \r\n★★YY可可地盘学习小组频道号码★★ \r\n★★★CalmSky的YY号码：295446119★★★",
                "pic": "http://dipan.kekenet.com/attachment/group/2015/tingxiejs.jpg",
                "membernum": "4606",
                "postnum": "12187",
                "isjoin": "0"
            },
            {
                "tagid": "865",
                "tagname": "每日翻译",
                "announcement": "本群组专为喜欢翻译以及希望通过翻译来提高英语运用能力的朋友建立，欢迎各位来此发布翻译信息以及回复内容，在交流中提高翻译能力。翻译是一种提高英语能力的有效办法，希望译群组能给各位带来帮助和乐趣。",
                "pic": "http://dipan.kekenet.com/attachment/group/2015/dailyfanyi.jpg",
                "membernum": "3096",
                "postnum": "19201",
                "isjoin": "0"
            },
            {
                "tagid": "947",
                "tagname": "每日短语",
                "announcement": "【每日短语听写小组】每天一句英语短语, 听力提高没有问题!",
                "pic": "http://dipan.kekenet.com/attachment/group/2015/dailyduanyu.jpg",
                "membernum": "266",
                "postnum": "700",
                "isjoin": "0"，
		  "isopen":0 //是否开放（是否允许发帖子）
            },
            {
                "tagid": "1840",
                "tagname": "病句批改",
                "announcement": "",
                "pic": "http://dipan.kekenet.com/attachment/group/2015/bingjupigai.jpg",
                "membernum": "10",
                "postnum": "43",
                "isjoin": "0"，
                "isopen":0 //是否开放（是否允许发帖子）
            },
            {
                "tagid": "1841",
                "tagname": "口语陷阱",
                "announcement": "每天推送一句我们日常生活中可能会遇到的英语口语陷阱。",
                "pic": "http://dipan.kekenet.com/attachment/group/2015/xianjing.jpg",
                "membernum": "96",
                "postnum": "2871",
                "isjoin": "0"，
                "isopen":0 //是否开放（是否允许发帖子）
            }
        ]
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
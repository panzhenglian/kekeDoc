# 话题回帖列表
**JSON 请求示例：**
```json
{
    "Token": "",
    "Params": {
           "PageIndex": 1,
           "PageSize": 20,
           "tid": 1 // 必须整数
    },
    "Method": "thread_postlist",
    "Terminal": "1",
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 310861
}
``` 
**JSON返回示例：**
```json
{
    "Code": 200,
    "Error": "",
    "Data": {
        "tagid": "18",//小组id
        "tid": 1,//话题列表id
        "subject": "男人是否应该打女人",
        "replynum": "13",回复数量
        "replylist": [
            {
                "pid": "1",话题内容id
                "msgtype": 0,信息类别 0 为普通信息 1 代表语音
                "message": "hehe", 信息内容
                "kouyu": "",
                "amr": "",
                "len": 10,
                "score": 0,
                "avatar": "http://uc.kekenet.com/data/avatar/000/31/08/61_avatar_middle.jpg",
                "username": "xuanjiang",
                "uid": "310861",
                "dateline": "1217496741",
                "ip": "58.83.245.23",
                "mp3": "",
                " ispraise":0,//是否点赞过
	         " praisecount":0,
                 "floor":11,
                 " replymsg":
			[{
                		"pid": "1",话题内容id
              		       "msgtype": 0,信息类别 0 为普通信息 1 代表语音
                             "message": "hehe", 信息内容
                             "kouyu": "",
                             "amr": "",
                             "len": 10,
                             "score": 0,
 				 "floor":11,
                             "avatar": "http://uc.kekenet.com/data/avatar/000/31/08/61_avatar_middle.jpg",
                            "username": "xuanjiang",
                            "uid": "310861",
                            "dateline": "1217496741",
       
          	  }]

            }
        ]
    },
    "Token": "",
    "PageIndex": 1,
    "PageSize": 20,
    "PageCount": 1,
    "IsDecode": 0,
    "Key": ""
}
```
# 话题列表(threadlist)
**JSON 请求示例：**
```json
{
    "Token": "",
"Params": {
"PageIndex": 1,
        "PageSize": 20,
        "tagid": 18 //必须 小组id， 必须整数
    },
    "Method": "thread_threadlist",
    "Terminal": "1",
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 310861 // 用户id 必须整数
}
```
**JSON返回示例：**
```json
{
    "Code": 200,
    "Error": "",
    "Data": {
        "tagid": "18",
        "tagname": "北京 上海",
        "announcement": "",
        "pic": "",
        "membernum": "219",//成员
        "postnum": "36",//帖子数量
        "isjoin": 0,// 0  表示没有加入 ，1 表示加入
        "isopen":0 ,//是否开放（是否允许发帖子）
        "thread": [
            {
                "tid": "1", //小组id
                "subject": "男人是否应该打女人",
                "uid": "310861",//用户id
                "avatar": "http://uc.kekenet.com/data/avatar/000/31/08/61_avatar_middle.jpg",//头像
                "username": "xuanjiang",//用户名
                "dateline": "1217496741",//发送时间
                "viewnum": "54826",// 总点击率
                "replynum": "13"// 回复次数
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
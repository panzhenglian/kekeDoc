# 添加文章评论
**JSON请求示例：**
```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "typeflag": 1,//0 为普通评论，1为回复评论
        "replyid": "1867100",//回复评论id//当typeflag 为1的时候，传值
        "newsid": "1416",//文章id
        "content": "好好你好好啊啊",//内容
        "username": "hello"//用户名
    },
    "Method": "v9_news_newscomment",
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
    "Msg": "您的评论提交成功！",
    "Error": "",
    "Data": {
        "commentid": "content_26-1416-1", //文章评论组合id
        "siteid": "1",
        "userid": 49, //用户id
        "username": "hello",//用户名
        " dateline": 1438770323,//创建时间
        "ip": "127.0.0.1",
        "status": "1",
        "content": "好好你好好啊啊",
        "direction": "0",
        "support": "0",
        "praisecount": 0,
        "replyid": "1867100",
        "terminal": 3,
        "typeflag": "1",
        "icon": "",
        "reply": {
            "id": "1867100",
            "terminal": "3",
            "replyid": "0",
            "commentid": "content_26-1416-1",
            "siteid": "1",
            "userid": "49",
            "username": "hello",
            " dateline ": "1438770324",
            "ip": "123.150.174.169",
            "status": "1",
            "content": "好好你好好啊啊",
            "direction": "0",
            "support": "0",
            "praisecount": "0",
            "reply": "0"
        },
        "id": 1867117,//评论id
        "address": "手机网友"
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
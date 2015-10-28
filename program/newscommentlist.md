# 文章评论列表
**JSON请求示例：**
```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "newsid": "1416",
        "PageIndex": 1,
        "PageSize": 20
    },
    "Method": "v9_news_newscommentlist",
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
    "Msg": "",
    "Error": "",
    "Data": [
       
        {
            "username": "hello",
            " dateline": "1438770323",
            "userid": "49",
            "typeflag": "1",
            "content": "好好你好好啊啊",
            "replyid": "1867100",
            "id": "1867117",
            "praisecount": "0",
            "support": "0",
            "ip": "127.0.0.1",
            "name": "hello",
            "address": "手机网友",
            "ispraise": 0,
            "icon": "http://uc.kekenet.com/data/avatar/000/00/00/49_avatar_middle.jpg",
            "reply": {
                "id": "1867100",
                "terminal": "3",
                "replyid": "0",
                "commentid": "content_26-1416-1",
                "siteid": "1",
                "userid": "49",
                "username": "hello",
                " dateline": "1438770324",
                "ip": "123.150.174.169",
                "status": "1",
                "content": "好好你好好啊啊",
                "direction": "0",
                "support": "0",
                "praisecount": "0",
                "reply": "0"
            }
        },
      
        {
            "username": "hello",
            "dateline": "1438770220",
            "userid": "49",
            "typeflag": "0",
            "content": "好好你好好啊啊",
            "replyid": "242",
            "id": "1867098",
            "praisecount": "0",
            "support": "0",
            "ip": "123.150.174.169",
            "name": "hello",
            "address": "天津市手机网友",
            "ispraise": 0,
            "icon": "http://uc.kekenet.com/data/avatar/000/00/00/49_avatar_middle.jpg"
        }
    ],
    "Token": "",
    "PageIndex": 0,
    "PageSize": 0,
    "PageCount": 0,
    "IsDecode": 0,
    "Key": ""
}
```

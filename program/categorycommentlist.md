# 节目评论列表
**JSON请求示例：**
```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "catid": "2146",//节目id，必须
        "PageSize": 20,
        "PageIndex": 1
    },
    "Method": "v9_news_categorycommentlist",
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
            "id": "6010", //评论id
            "praisecount": "0",//点赞数
            "username": "hello",//用户名称
            "catid": "2146",//节目id
            "userid": "49",//用户id
            "content": "好好",//评论内容
            "dateline": "1438760030",//时间
            "ip": "127.0.0.1",//IP
            "replyid": "242",//回复id
            "typeflag": "1",//0为普通评论，1位回复
            "replycount": "0",//回复数
            "address": "nn手机网友", //网友上网的地址
            "ispraise": 0,//登陆用户 ，是否点过赞
            "icon": "http://uc.kekenet.com/data/avatar/000/00/00/49_avatar_middle.jpg",//用户头像
            "reply": { //回复信息 typeflag 为1 的时候才有reply
                "id": "242",//评论id
                "praisecount": "0",//点赞数
                "catid": "2146",//节目id
                "siteid": "1",//站点类别
                "userid": "1844924",//用户id
                "username": "nicolechoi", //用户名
                "content": "，g", //内容
                "dateline": "1423100356",//时间
                "ip": "mobile", //ip
                "typeflag": "0",
                "replycount": "0",
                "replyid": "0"
            }
        },
        {
            "id": "6009",
            "praisecount": "0",
            "username": "hello",
            "catid": "2146",
            "userid": "49",
            "content": "好好",
            "dateline": "1438759142",
            "ip": "127.0.0.1",
            "replyid": "0",
            "typeflag": "0",
            "replycount": "0",
            "comment": "好好",
            "address": "nn手机网友",
            "ispraise": 0,
            "icon": "http://uc.kekenet.com/data/avatar/000/00/00/49_avatar_middle.jpg"
        }
 
    ],
    "Token": "",
    "PageIndex": 1,
    "PageSize": 20,
    "PageCount": 1,
    "IsDecode": 0,
    "Key": ""
}
```
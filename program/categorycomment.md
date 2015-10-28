# 添加节目评论
**JSON请求示例：**
```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "typeflag": 1,//评论类别 0 为添加评论，1为回复评论 //必须
        "replyid": "",//当typeflag 为1的时候传 评论id//可选
        "catid": "2296",//节目id //必须
        "content": "好好",//内容 //必须
        "username": "hello"// 登陆人名称//必须
    },
    "Method": "v9_news_categorycomment",
    "Terminal": 3,
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 49 //用户id
}
```
 
**JSON返回示例：**
```json
{
    "Code": 200,
    "Msg": "您的评论提交成功！",
    "Error": "",
    "Data": {
        "catid": "2146",//节目id
        "siteid": "1",//
        "userid": 49,//用户id
        "username": "hello",//用户名
        "dateline": 1423100355,//时间
        "ip": "123.116.114.153",//ip
        "content": "好好你好好啊啊",
        "replyid": "242",//typeflag=1 时才有
        "typeflag": 1,//0 为正常评论，1为回复评论
        "praisecount": 0,
        "id": 6019,//评论id
         "icon":"",
        "reply": { typeflag=1 时才有 回复信息
            "id": "242",
            "praisecount": "0",
            "catid": "2146",
            "siteid": "1",
            "userid": "1844924",
            "username": "nicolechoi",
            "content": "，g",
            " dateline": "1423100356",
            "ip": "mobile",
            "typeflag": "0",
            "replycount": "0",
            "terminal": null,
            "replyid": "0"
        },
        "address": "手机网友" //网友地址
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
# 搜索通知信息
**JSON 请求示例：**
```json
{
    "Token": "",
    "Params": {
        "PageIndex": 1,
        "PageSize": 1,
        "new": 1, //通知是否为新:'1'为新通知,'0'为通知已读（可选）
        "type": "post" //  post 为小组，不传为系统通知
    },
    "Method": "notification_searchmsg",
    "Terminal": 3,
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 379899
}
```
**JSON返回示例：**
```json
{
    "Code": 200,
    "Error": "",
    "Data": [
        {
            "type": "friend",//类型
            "new": "1",//1 表示新消息，0 表示已读
            "authorid": "534198",//发送人id
            "author": "Cameline",//发送人名称
            "note": "1286638680",// 消息内容
            "dateline": "1286638680",// 时间
            "icon": http://uc.kekenet.com/data/avatar/000/53/41/98_avatar_big.jpg  //发送人头像
        }
    ],
    "Token": "",
    "PageIndex": 1,
    "PageSize": 20,
    "PageCount": 1,
    "IsDecode": 0//0 表示不加密，1 表示加密
}    
```
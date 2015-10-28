# 搜索私信
**JSON 请求示例：**
```json
{
    "Token": "",
    "Params": {
"AddTime": 1, //最后一点的时间
"touid": 1,//接受人的id
         "PageSize": 20
    },
    "Method": "msg_searchmsg",
    "Terminal": "1",
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": "49"
}
```
**JSON返回示例：**
```json
{
    "Code": 200,
    "Error": "",
    "Data": [
        {
            "len": "6",
            "typeflag": "1", // 
            "mid": "61",
            "uid": "49",
            "username": "",
            "touid": "72920",
            "tousername": "zhouxy",
            "dateline": "1431422137",
            "isread": "0",
            "msg": "",
            "path": "/app/upload/15/05/12/49/1431422137.amr",// type   为1的时候是语音地址，2为图片地址
            "uidicon": "http://uc.kekenet.com/data/avatar/000/00/00/49_avatar_big.jpg",
            "toicon": "http://uc.kekenet.com/data/avatar/000/07/29/20_avatar_big.jpg"
        } 
    ],
    "Token": "",
    "PageIndex": 1,
    "PageSize": 20,
    "PageCount": 4,
    "IsDecode": 0
}
```
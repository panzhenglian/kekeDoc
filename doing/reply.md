# 回复动态（回复-回复）
**JSON 请求示例：**

```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "message": "",
        "username": "hedeyong",
        "content": "aGVsbG8=",//语音内容
        "doid": 341159,//楼主id
        "upid": 640802,//回复id
        "contentflag": 1,//1 表示语音，0表示文本
        "timelen": 11//语音长度
    },
    "Terminal": 3,
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 163898,
    "Method": "doing_reply"
}
```
**JSON返回示例：**

```json
{
    "Code": 200,
    "Msg": "",
    "Error": "",
    "Data": {
        "doid": 341159,
        "upid": 640802,
        "uid": 163898,
        "username": "hedeyong",
        "touid": 163811,
        " tousername": "hedeyong",//
        "message": "",
        "dateline": 1439368589,
        "icon":"",//回复人头像
        "contentflag": 1,
        "grade": 2,
        "fileurl": "http://mp3.kekenet.com/dipan//msg/voice/2015/08/1439368589.amr",
        "timelen": 11,
        "replyid": 640803 //回复人id
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
# 回复楼主
**JSON 请求示例：**

```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "message": "",//
        "username": "hedeyong",
        "content": "aGVsbG8=",//语音内容
        "doid": 341159,//楼主id 必须
        "contentflag": 1,//0 表示文本，1 表示音频（回复只能有两种 只能是文本或者语音）必须
        "timelen": 11//语音长度
    },
    "Terminal": 3,
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 163898,
    "Method": "doing_replyhost"
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
        "uid": 163898,
        "username": "hedeyong",
        "message": "",
        "dateline": 1439367109,
        "icon":"",
        "contentflag": 1,
        "grade": 1,
        "fileurl": "http://mp3.kekenet.com/dipan//msg/voice/2015/08/1439367109.amr",
        "timelen": 11,
        "replyid ": 640802
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
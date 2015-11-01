# 添加动态
**JSON 请求示例：**

```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "message": "您好！！",
        "username": "hedeyong",
        "location": "",
        "attachments": [
            {
                "fileurl": " http://mp3.kekenet.com/dipan//doing/voice2015/08/2EAED88D0A723B4DB43D9FAB1ACC3A5B.amr", //上传后的url
                "contentflag": 1,//1表示语音，2 表示图片
                "filename": "amr",//扩展名不包括“.”
                "sortnum": 0,//上传图片的时候有用（图片顺序）
                "timelen": 11 //语音长度
            }
        ]
    },
    "Terminal": 3,
    "Version": "2.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 163898,
    "Method": "doing_add"
}
```
**JSON返回示例：**

```json
 {
    "Code": 200,
    "Msg": "",
    "Error": "",
    "Data": {
        "uid": 163898,
        "username": "hedeyong",
        "message": "您好！！",
        "dateline": 1439362595,
        "mobiletype":" android",
         "location ":"beij",
        "clickrate": "0",//点击率
        "ispraise": 0,//是否点赞过，0 未点赞，1点赞过
        "attachments": [
            {
                "contentflag": 1,
                "sortnum": 0,
                "fileurl": "http://mp3.kekenet.com/dipan//msg/voice/2015/08/1439362595.amr",//文件地址
                "timelen": 11,//语音长度
            }
        ],
        "doid": 341159
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
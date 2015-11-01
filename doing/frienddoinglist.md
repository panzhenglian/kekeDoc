# 朋友动态列表
**JSON 请求示例：**

```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "userid": "49",
        "PageIndex": 1,
        "PageSize": 1
    },
    "Terminal": 3,
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 163898,
    "Method": "doing_frienddoinglist"
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
            "doid": "345680",//动态id
            "uid": "546925",//用户id
            "username": "Julie墨迹", //用户名
            "message": "如果你打算回来，我不需再多的言语。", //文本内容
            "location": "",//位置
            "clickrate": "0",//点击率（浏览数）
            "ispraise": 0,//是否点赞过 0 未点赞，1点赞
            "dateline": "1439450688",//发布时间
            "mobiletype":"android",
            "attachments": [ //附件列表  
                {
                    "fileurl": "http://mp3.kekenet.com/dipan//msg/voice/2015/08/1439362538.amr",
                    "contentflag": "1",
                    "timelen": "11",
                    "sortnum":0
                }
            ],
            "praiselist":  [
                    {
                        "username": "hedeyong",
                        "uid": "163898",
                        "icon": "http: //uc.kekenet.com/data/avatar/000/16/38/98_avatar_big.jpg"
                    }
                ] ,
            "praisecount": "0",//点赞数量
            "icon": "http: //uc.kekenet.com/data/avatar/000/54/69/25_avatar_big.jpg",
            "replynum": "0",//回复数量
            "reply": [
                {
                    "replyid ": "650141",//回复id
                    "message": "",//文本
                    "uid": "613832",
                    "username": "talant",
                    "touid": "",
                    "grade":1,
		      "timelen":12,
                    "icon":"",
                    "toicon":"",
                    "tousername": "",
                     "contentflag":1,//0 表示文本，1 表示语音
                     "fileurl":" http://mp3.kekenet.com/dipan//msg/voice/2015/08/1439362538.amr ",
                }
            ]
        }
    ],
    "Token": "",
    "PageIndex": 1,
    "PageSize": 1,
    "PageCount": 290367,
    "IsDecode": 0,
    "Key": ""
}
```
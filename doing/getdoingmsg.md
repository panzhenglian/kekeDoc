# 获取动态信息
**JSON 请求示例：**

```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "doid": 400288
    },
    "Terminal": 3,
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 163898,
    "Method": "doing_getdoingmsg"
}
```
**JSON返回示例：**

```json
{
    "Code": 200,
    "Msg": "",
    "Error": "",
    "Data": {
        "doid": "341158",//动态id
        "uid": "163898",//用户id
        "username": "hedeyong",//名称
        "message": "您好！！",//内容信息
        "location": “”,//位置信息
        "clickrate": "0",//点击率
        "ispraise": 0,//是否点赞过，0 未点赞，1点赞过
        "dateline": "1439362537",//发布时间
        "mobiletype":"android",
        "attachments": [
            {
                "fileurl": "http://mp3.kekenet.com/dipan//msg/voice/2015/08/1439362538.amr",//语音地址
                "contentflag": "1",//内容标记，1 为语音，2 为图片
                "timelen": "11",//语音长度
                "sortnum": 0,//上传图片的时候有用（图片顺序）
            }
        ],
        "praiselist": {
         
             {
                "username": "hedeyong",//用户名
                "uid": "163898",//用户id
                "icon": ""http://uc.kekenet.com/data/avatar/000/16/38/98_avatar_big.jpg"           
            }
 
        },
        "praisecount": "0",
        "icon": "http://uc.kekenet.com/data/avatar/000/16/38/98_avatar_big.jpg",
        "replynum": "0",
        "reply": [
          {
                    "id": "650141",
                    "message": "",
                    "uid": "613832",
                    "username": "talant",
                    "touid": "",
                    "tousername": "",
                    "icon":"",
                    "toicon":"",
                     "contentflag":1,//0 表示文本，1 表示语音
                     "fileurl":"http://mp3.kekenet.com/dipan//msg/voice/2015/08/1439362538.amr",
               
                }
        ]
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
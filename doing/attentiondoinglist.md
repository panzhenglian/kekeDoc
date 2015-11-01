# 关注-动态列表
**JSON 请求示例：**

```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "PageIndex": 1,
        "PageSize": 1
    },
    "Terminal": 3,
    "Version": "2.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 163898,
    "Method": "doing_attentiondoinglist"
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
            "doid": "345404",//动态id
            "uid": "3002115",//发布人id
            "username": "ilov000",//发布人名称
            "message": " i got five friends yesterday,very happy.hope we can improve english together",//内容
            "location": null,//位置
            "clickrate": "0",//点击率
            "ispraise": 0,//是否点赞
            "dateline": "1438841959",//发布时间
                 "attachmentlist": [
            {
                "fileurl": "http://mp3.kekenet.com/dipan//msg/voice/2015/08/1439362538.amr",//语音地址
                "contentflag": "1",//内容标记，1 为语音，2 为图片
                "timelen": "11"//语音长度
            }
        ],
        "praiselist": {
             {
                "username": "hedeyong",//用户名
                "uid": "163898",//用户id
                "icon": ""http://uc.kekenet.com/data/avatar/000/16/38/98_avatar_big.jpg"           
            }
        },
            "praisecount": "0",//点赞数
            "contentflag": 0,//内容类型
            "icon": "http://uc.kekenet.com/data/avatar/003/00/21/15_avatar_big.jpg",
            "replynum": "0",//回复数
            "mobiletype": "pc",//手机类型
            "reply": [
                {
                    "id": "649696",
                    "message": "Gyhffthdrjc",
                    "uid": "3015371",
                    "username": "keke3015371",
                    "touid": "",
                    "tousername": "",
                    "contentflag": 0,
                    "mp3url": "",
                    "grade": "1"
                }
            ]
        }
    ],
    "Token": "",
    "PageIndex": 1,
    "PageSize": 1,
    "PageCount": 3077,
    "IsDecode": 0,
    "Key": ""
}
```
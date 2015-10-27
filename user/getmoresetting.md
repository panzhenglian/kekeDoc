# 获取个人更多设置
**JSON请求示例：**
```js
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params":””,
    "Method": "customer_getmoresetting",
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
    "Error": "",
    "Data": {
        "username": "bluewhite",
        "icon": "http://uc.kekenet.com/data/avatar/000/00/00/49_avatar_middle.jpg",
        "fans": { // 粉丝信息
            "num": "1",//数量
            "newsflag": 0 //是否有最新粉丝 0代表没有，1代表有
        },
        "singnum": 1,
        "thread": {//帖子信息 
            "num": "0",//数量
            "newsflag": 0 //是否有最新 帖子 0 代表没有，1 代表有
        },
        "attentionnum": "1",//关注数量
"msgcount": "0",// 消息数量
"listencount":12,//收听数
        "levelinfo": { //等级信息
            "level": 1,//等级
            "title": "初级可友",//等级名称
            "total": "1118" // 总的积分（金币）
        }
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
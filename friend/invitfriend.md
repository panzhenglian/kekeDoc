# 邀请朋友
**JSON请求示例：**

```json
{
    "Token": "C4AD5BC8FE6BAE65640CCF6E51DFCC8E",
    "Params": {
 
    }, 
    "Method": "friend_invitfriend",
    "Terminal": 3,
    "Version": "2.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 2929415
}
```
**JSON返回示例：**

```json
{
    "Code": 200,
    "Msg": "",
    "Error": "",
    "Data": {
        "description": "邀请好友得keke豆 20", //邀请描述
        "authcode": "tENNfn2929415",//邀请码
        "todaycount": 0,//今天邀请的人数
        "todaypoint": 0,//今日邀请获取的积分
        "total": 0,//邀请总的人数
        "totalpoint": 0//邀请获取的总的积分
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
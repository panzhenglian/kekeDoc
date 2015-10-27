# 获取消息中心
**JSON请求示例：**
```json
{
    "Token": "",
    "Params": "",
    "Method": "customer_messageceneter",
    "Terminal": 3,
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 254055
}
```

**JSON返回示例:**
 
```json
{
    "Code": 200,
    "Error": "",
    "Data": {
        "msgcenter": {
            "msg": {
                "count": 1,//总的数量
                "list": [
					{
                        "num": "5",//发送的数量
                        "uid": "2189325",//发送人ID
                        "username": "keke2189325",// 发送人名称
                        "icon": "http://uc.kekenet.com/data/avatar/002/18/93/25_avatar_big.jpg",
                        "msg": "呃",//信息内容
                        "typeflag": "0",//信息类型 0 为文本 1 为音频 2 为图片
                        "path": "", //音频或者图片路径
                        "dateline": "1436499112"
                    }
				]
            },
            "notification": { //系统通知
                "count": 21,
                "content": {
                    "type": "wall", //系统通知类型(扩展)
                    "new": "1",// （扩展）
                    "authorid": "2118867",//发送人id
                    "author": "天下第衣铺",//发送人名称
                    "msg": "在留言板上给你留言</a>",//具体信息
                    "dateline": "1414501186",
                    "icon": "http://uc.kekenet.com/data/avatar/002/11/88/67_avatar_big.jpg"
                }
            },
            "post": { //小组
                "count": 5,
                "content": {
                    "type": "post",//扩展
                    "new": "1",//扩展
                    "authorid": "454254",// 发送人id
                    "author": "jevons1674",//发送人姓名
                    "msg": "回复了你的话题 Thing do not change; we change",//内容信息
                    "dateline": "1238509462",
                    "icon": "http://uc.kekenet.com/data/avatar/000/45/42/54_avatar_big.jpg"
                }
            }
        },
        "count": 27
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
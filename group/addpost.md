# 添加回帖
**JSON 请求示例：**
```json
{
    "Token": "3d89386cdf2f92c8b4f3f700262f5537",
    "Params": {
        "tagid": 18, // 组id
        "len": 0,// 音频的长度（发语音的时候）
        "msg": "发动机", //发送内容
        "msgtype": 0, //0 表示普通信息，1 表示语音,2 图片
        "score": 18,
        "username": "jacky", //用户名
        "voice": "",语音base64内容
        "pid": 562013, //回复id
        "tid": 400661 //话题列表id,
       
    },
    "Method": "thread_addpost",
    "Terminal": "1",
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 310861
}
```
 
**JSON返回示例：**
```json
{
    "Code": 200,
    "Error": "",
    "Data": {
        "tid": 400661,
        "pid": 562015
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
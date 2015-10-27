# 获取任务信息
**JSON请求示例：**
```json
{
    "Token": "",
    "Params": {
        "type": 1 //任务类型 1为分享好友 ，2 内容分享， 3 为收听
    },
    "Method": "customer_gettaskmsg",
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
        "uid": "2284607",
        "date": 1436868123,
        "num": 0, //今天次数
        "point": 0, //今日分数
        "count": 4, //总次数
        "allpoint": 400, //总分数
        "summary": "每日分享到微信或者朋友圈就能获取到50-100可可豆" // 描述说明
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
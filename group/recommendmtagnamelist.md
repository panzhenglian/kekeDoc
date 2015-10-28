# 小组推荐名称列表（发现小组）
**JSON 请求示例：**
```json
{
    "Token": "",
    "Params": [],
    "Method": "thread_recommendmtagnamelist",
    "Terminal": "1",
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 2182534
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
            "title": "精品小组", //名称
            "type": "hotgroup" //类别
        },
        {
            "title": "每日系列",
            "type": "daily"
        },
        {
            "title": "实用英语",
            "type": "english"
        },
        {
            "title": "视频音乐",
            "type": "movie"
        }
    ],
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
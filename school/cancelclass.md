# 取消学堂课程
**JSON请求示例：**

```json
{
	"Method": "v9_news_cancelclass",
	"UID": "2793192",
	"Version": "2.0",
	"Lat": "",
	"Lng": "",
	"Params": {
		"catid": "96", //节目id（课程id） //必须
              "searchtype":0 //搜索类型 0 表示听力，1 表示口语 //默认0
	},
	"Token": "4EB5AE049AC0FA719B5D4843B953C784",
	"Terminal": 3
}
```

**JSON返回示例：**

```json
{
    "Code": 200,
    "Msg": "",
    "Error": "",
    "Data": {
        "status": 1 //1 成功，0 失败 
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
# 获取节目订阅列表
**JSON请求示例：**
```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "userid": 163898
    },
    "Terminal": 3,
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 2284607,
    "Method": "customer_usercolumnlist"
}
```
**JSON返回示例： 默认100**
```json
{
    "Code": 200,
    "Error": "",
    "Data": [
        {
            "catid": "15328",//类别id
            "lmpic": "http://pic.kekenet.com/column/201411/1417095027.jpg",//背景图
            "catname": "英语六级分类阅读训练附解析",//节目名称
            "num": "1203" ,//订阅量
	         "dateline": "2012-12-03 16:35:59",
            "articlecount": "96"
        },
        {
            "catid": "15093",
            "lmpic": "http://pic.kekenet.com/column/201411/1417256387.jpg",
            "catname": "英语六级词汇拼读版",
            "num": "1132",
"dateline": "2012-12-03 16:35:59",
            "articlecount": "96"

        }
    ],
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
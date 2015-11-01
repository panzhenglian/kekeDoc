# 获取学堂首页
**JSON请求示例：**

```json
{
    "Token": "fe95d19f1d8ccf8e4a2f5681b91dc87c",
    "Params": {
       
    },
    "Method": "v9_news_getclassindex",
    "Terminal": "2",
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": "202921"
}
```
**JSON返回示例：**

```json
{
    "Code": 200,
    "Msg": "",
    "Error": "",
    "Data": {
        {
            "title": "听力训练",//标题
            "searchtype": 0, //搜索类型
            "count": 12,
            "icon": "",
	     "desc":"",
	     "desc":"",
	    "is_open: 1//1 代表开发，0不开发
        },
         {
            "title": "口语训练",
            "count": 12,
            "searchtype": 1,
            "icon": "",
            "desc":""，
           "is_open: 0//1 代表开发，0不开发

        }
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
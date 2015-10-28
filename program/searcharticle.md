# 搜索文章
**JSON请求示例：**
```json
{
    "Params": {
        "PageIndex": 1,
        "PageSize": 20,
        "Sort": " id desc",
        "Catids": "2296",
        "KeyWord": "热门"
    },
    "Method": "v9_news_searcharticle",
"Terminal": "1",//0 为 pc，1为iphone,2为ipad,3为安卓，4为WP，5为QQ，6为新浪微博，7为微信  
  "Version": "1.0",
    "Lat": "",
    "Lng": ""
}
```
 

**JSON返回示例：**
```json
{
    "Code": 200,
    "Error": "",
    "Data": [
        {
            "fileurl": "",
            "title": "新加坡留学:时尚高薪热门的设计专业",
            "lmpic": "",
            "thumb": "",
            "id": "161355",
            "updatetime": "2011-11-16",
            "download": "",
            "switch": 0,
            "type": 1,
            "catname": "专业选择",
            "catid": "2296"
        },
        {
            "fileurl": "",
            "title": "盘点今年新加坡热门留学专业",
            "lmpic": "",
            "thumb": "",
            "id": "159350",
            "updatetime": "2011-10-31",
            "download": "",
            "switch": 0,
            "type": 1,
            "catname": "专业选择",
            "catid": "2296"
        } 
    ],
    "Token": "",
    "PageIndex": 1,
    "PageSize": 20,
    "PageCount": 1,
    "IsDecode": 0//0 表示不加密，1 表示加密
}
```
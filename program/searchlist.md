# 搜索听说节目（（全部-听-说-读）的听-说）
>请求有两种  

**1.0 JSON请求示例：**
```json
{
    "Token": "",
"Params": {
    "PageIndex": 1,
    "PageSize": 1,
        "searchtype": 1, //0 表示 搜索听，1 表示搜索口语
        "kouyusort": 4,//搜索等级 1-9 默认0 
        "Sort": "updatetime asc" // 按照实际排序 asc升序， desc 是降序  排序的有（updatetime，views （点击率），subscription） ；
    },
    "Method": "v9_news_searchlist",
    "Terminal": 3,
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 332940
}
```

**2.0 JSON请求示例：**
```json
{
    "Token": "",
"Params": {
    "PageIndex": 1,
    "PageSize": 1,
        "searchtype": 0, //0 表示 搜索听，1 表示搜索口语
        " listenlevel": 6,//搜索等级 1-8 默认0 
        "Sort": "updatetime asc" // 按照实际排序 asc升序， desc 是降序  排序属性有（updatetime，views （点击率）） ；
    },
    "Method": "v9_news_searchlist",
    "Terminal": 3,
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 332940
}
```
**JSON返回示例：**
```json
{
    "Code": 200,
    "Error": "",
    "Data": [
        {
            "catid": "15213",
            "catname": "家园纪录片",
            "is_book": "1",
            "rank": "3",
            "guanzhu": "907",
            "num": 38,
            "lmpic": "http://pic.kekenet.com/column/201410/1414421039.jpg",
            "updatetime": "2014-11-17",
            "close": "0",
            "ting": "1",
            "type": 3,
            "topid": "15289",
            "topname": "TED公开课"
        } 
    ],
    "Token": "",
    "PageIndex": 1,
    "PageSize": 20,
    "PageCount": 1,
    "IsDecode": 0,
    "Key": ""
}
```
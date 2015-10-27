# 获取子栏目信息
**JSON请求示例：**
```json
{
    "Token": "bd6c476550a0ef99526645961f2e6d1e",
    "Params": {
        "PageIndex": 1,
        "PageSize": 20,
        "catid": 15332 //节目id
    },
    "Method": "v9_news_getsubcategorys",
    "Terminal": 3,
    "Version": "1.0",
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
    "Data": [
        {
            "is_book": "0",
            "rank": "3",
            "catid": "13569",
            "catname": "AP News",//节目名称
            "guanzhu": "200",//关注数
            "lmpic": "http://pic.kekenet.com/column/201503/1425898048.jpg",
            "num": 1140,//文章数
            "updatetime": "2015-08-24",
            "close": "1",
            "ting": "1",
            "type": 1,
            "topid": "13569",//父id
            "topname": "AP News"//父名称
        }
    ],
    "Token": "",
    "PageIndex": 1,
    "PageSize": 1,
    "PageCount": 1,
    "IsDecode": 0,
    "Key": ""
}
```
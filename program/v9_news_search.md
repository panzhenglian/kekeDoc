# 搜索文章/节目
**JSON1.0 搜索文章请求示例：**
```json
{
    "Token": "",
    "Params": {
        "PageSize": 2,
        "PageIndex": 1,
        "searchtype": 0,// 0代表 搜索文章，1 代表搜索节目 （可选，默认为文章）
        "Catids": "10001,817", //搜索的类别ID，多个类别以逗号分开 （可选）
        "KeyWord": "每日",//搜索的关键词 （可选）
        "Filter": "CNN,ABC,NPR,PBS,FOX,BBC" // 需要过来的关键词 ，多个以逗号分开。（可选）
    },
    "Method": "v9_news_search",
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
    "Data": [
        {
            "title": "空中美语中级每日在线听[20150706]",//文章标题
            "lmpic": "http://pic.kekenet.com/column/201412/1419488878.jpg",//图片
            "thumb": "",
            "id": "385052",//文章id
            "updatetime": "2015-07-10",
            "download": "Sound/2015/07/mid4uu20150706_3511213XAq.mp3",//mp3下载地址
            "switch": 0,
            "type": 2, //类别 2 代表mp3
            "catname": "空中美语中级",//类别名称
            "catid": "153" //类别ID
        }
    ],
    "Token": "",
    "PageIndex": 1,
    "PageSize": 1,
    "PageCount": 2824,
    "IsDecode": 0,
    "Key": ""
}
```
**JSON2.0 搜索节目请求示例：**
```json
{
    "Token": "",
    "Params": {
        "PageSize": 2,
        "PageIndex": 1,
        "searchtype": 1,// 0代表 搜索文章，1 代表搜索节目 （可选，默认为文章）
        "Catids": "10001,817", //搜索的类别ID，多个类别以逗号分开 （可选）
        "KeyWord": "每日",//搜索的关键词 （可选）
        "Filter": "CNN,ABC,NPR,PBS,FOX,BBC" // 需要过来的关键词 ，多个以逗号分开。（可选）
    },
    "Method": "v9_news_search",
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
    "Data": [
        {
            "is_book": "0",//是否为系列
            "rank": "3",//基本 1为初级，2为中级，3 为高级
            "catid": "79",//节目id
            "catname": "VOA常速英语",//节目名称
            "guanzhu": "5890",//订阅量
            "lmpic": "http://pic.kekenet.com/column/201501/1422696886.jpg",//图片
            "num": 7895,//文章数目
            "updatetime": "2015-07-13",//更新时间
            "close": "1",
            "ting": "1",//
            "type": 1,
            "topid": "79",//上级类别id
            "topname": "11"//上级类别名称
        }
    ],
    "Token": "",
    "PageIndex": 1,
    "PageSize": 1,
    "PageCount": 1631,
    "IsDecode": 0,
    "Key": ""
}
```
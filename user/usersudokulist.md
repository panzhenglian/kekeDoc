# 九宫格列表
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
    "Method": "customer_usersudokulist"
}
```
**JSON返回示例： 默认100**
```json
 {
    "Code": 200,
    "Error": "",
    "Data": [
        {
            "news_id": "368387",
            "title": "纪录片《鲸奇之旅Ocean Voyagers》(MP3+中英字幕) 第13期:鲸奇之旅(2)",
            "score": "15", //得分
            "time": "37566",//耗时
            "updatetime": "2015-04-10",
            "catid": "15528",//类别id
            "catname": "纪录片《鲸奇之旅Ocean Voyagers》",//类别名
            "type": 3
        },
        {
            "news_id": "257033",
            "title": "《那些年那些诗》第73篇:园丁集 16 The Gardener 16",
            "score": "1",
            "time": "15",
            "updatetime": "2015-04-10",
            "catid": "13636",
            "catname": "那些年那些诗",
            "type": 3
        }
    ],
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
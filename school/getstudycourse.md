# 获取听内容
**JSON请求示例：**

```json
{
    "Method": "v9_news_getstudycourse",
    "UID": "2793192",
    "Version": "2.0",
    "Lat": "",
    "Lng": "",
    "Params": {
        "id": 379492 //文章id
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
        "title": "BBC双语新闻讲解附字幕:国际足联前官员布莱泽详述受贿案",
        "content": [
            {
                "en": "BBC News with Joe Mocintosh.",
                "cn": "乔·麦金塔什为你播报BBC新闻。",
                "time": "00:00.00",
                "millisecond": 0
            },
            {
                "en": "A 40-page dossier has been released by the US Justice Department,",
                "cn": "美国司法部公布了一份40页的文件，",
                "time": "00:03.34",
                "millisecond": 3340
            },
            {
                "en": "in which the former FIFA official Chuck Blazer gives a detailed account of the corruption he says was at the heart of world football's governing body.",
                "cn": "国际足联前官员恰克·布莱泽在文件中详细叙述了该世界足球官方机构中存在腐败现象。",
                "time": "00:07.44",
                "millisecond": 7440
            },
             
        ],
        "mp3": "Sound/2015/06/bbc0609_1044324hWe.mp3", //
        "lrc": "Sound/2015/06/71bd99c1155f91acd2ac.lrc",
        "type": "3",
        "switch": "0",
        "catid": "15428",
        "catname": "2015年上半年BBC新闻",
        "lmpic": "http://pic.kekenet.com/column/201501/1420421142.jpg",
        "ting": "1",
        "commentcount": "0",
        "shareurl": "http://m.kekenet.com/broadcast/201506/379492.shtml"
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
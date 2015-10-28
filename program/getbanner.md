# 获取banner
**JSON请求示例：**
```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {},
    "Method": "v9_news_getbanner",
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
            "banner": "http://mob2014.kekenet.com/apptest/upload/15/07/16/1437048154jdt6rhymes.jpg",// banner 图
            "title": "英国爷爷儿歌大全",//标题
            "lmpic": "http://pic.kekenet.com/column/201505/1431311369.jpg",//缩略图
            "id": "15619",// 节目id catid
            "is_book": 0,  //是否为系列文章
            "type": "0"//0 表示列表 1 表示文章，2 表示小组
        },
        {
            "banner": "http://mob2014.kekenet.com/apptest/upload/15/07/16/1437047060ad_w240_002.jpg",
            "title": "听小故事学英语",
            "lmpic": "http://pic.kekenet.com/column/201505/1431053120.jpg",
            "id": "15616",
            "is_book": 0,
            "type": "0"
        },
        {
            "banner": "http://mob2014.kekenet.com/apptest/upload/15/07/16/1437048080jdt6dog.jpg",
            "title": "BBC纪录片《萌犬秘闻》",
            "lmpic": "http://pic.kekenet.com/column/201505/1431311446.jpg",
            "id": "15618",
            "is_book": 0,
            "type": "0"
        }
    ],
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
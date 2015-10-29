# 单词库
**JSON 请求示例：**  
```json
{
    "Token": "3d89386cdf2f92c8b4f3f700262f5537",
    "Params": {
 
    },
    "Method": "word_getwordlibrarys",
    "Terminal": "1",
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": "2958902" 
}
```
**JSON返回示例：**
```json
{
    "Code": 50004,
    "Msg": "",
    "Error": "",
    "Data": [
        {
            "catname": "小学中学",
            "content": [
                {
                    "title": "小学英语必备单词",
                    "count": 1986,
                    "passcount": 133,
                    "cid": 574,
                    "dburl": "http://mob2015.kekenet.com/exploitation/files/words/library/574.7z", //数据库下载地址
                    "mp3url": "http://mob2015.kekenet.com/exploitation/ files/words/library/574mp3.7z"//mp3 下载地址
                },
      
    ],
    "Token": "fySvbi2DDrzO9IEMSYOY9PwQ+F8XmdqibrN6cxc8Q2M=",
    "IsDecode": 0,
    "Key": "GO7AJa6zpqWLyvk4y1j1eQ=="
}
```
# 划词
**JSON 请求示例：**
```json
{
    "Token": "3d89386cdf2f92c8b4f3f700262f5537",
    "Params": {
          "word":"word"
    },
    "Method": "word_movesearch",
    "Terminal": "1",
    "Version": "2.0",
    "Lat": "100",
    "Lng": "444",
    "UID": "2958902" 
}
```
**JSON返回示例：**
```json
{
    "Code": 200,
    "Msg": "",
    "Error": "",
    "Data": 
        {
            "word": "word",
            "pronunciation": "mp3/108/0631eb9d4249941736475203e5f399b7.mp3",
            "spell": "[wə:d]",
            "meaning": "n. 单词；话语；消息；诺言；命令\nvt. 用言辞表达\n"
        }
    ,
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
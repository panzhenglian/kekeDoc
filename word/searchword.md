# 单词搜索
**JSON 请求示例：**
```json
{
    "Lat": "",
    "Lng": "",
    "Method": "word_searchword",
    "Params": {
        "word": "ok"
    },
    "Token": "1D8A70312A2221ED2728D8500640EC4B",
    "UID": "2929415",
    "Version": "1.0",
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
        "word": {
            "id": "48120",
            "word": "ok",
            "pronunciation": "mp3/48/95b09e675977f8ec84216e39bdb77478.mp3",
            "spell": "['əu'kei, ,əu'kei, 'əukei]",
            "meaning": "adj. 好的；不错的\nadv. 行；很好\nint. 好；可以\nvt. 对…表示同意\nn. 同意\n",
            "meaning_analyse": "",
            "root": ""
        },
        "example": [
            {
                "en": "Treasure each other, OK?",
                "cn": "彼此珍重，好不好？",
                "voice": "http://mp3.kkdict.com/mp3/example/128/7f53da17dad66638312f8ab6c23cf399.mp3"
            },
            {
                "en": "OK , A wave and a bride – make – up .",
                "cn": "好的，头发烫一下，再做个新娘化妆。",
                "voice": "http://mp3.kkdict.com/mp3/example/128/17f1c3777e2dce1dc50d8a05e3da5851.mp3"
            },
            {
                "en": "OK, more news and discussion of this topic.",
                "cn": "好了，更多的新闻和讨论这个话题。",
                "voice": "http://mp3.kkdict.com/mp3/example/128/4ef5ee03400d92d3aa8ec73dc559190a.mp3"
            }
        ],
        "tongyi": [
            {
                "cixing": "r",
                "danci": "all right,alright,fine,very well"
            },
            {
                "cixing": "n",
                "danci": "okay,oklahoma,sooner state"
            },
            {
                "cixing": "a",
                "danci": "all right,fine,hunky-dory"
            }
        ],
        "fanyi": [],
        "bianxi": "",
        "analyse": [],
        "entype1": "n",
        "enmeaning1": "being satisfactory or in satisfactory condition",
        "enmeaning2": "an expression of agreement normally occurring at the beginning of a sentence",
        "entype2": "adj"
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
# 文章生词列表
**JSON 请求示例：**
```json
{
    "Token": "fe95d19f1d8ccf8e4a2f5681b91dc87c",
    "Params": {
        "id": "379491",
         "searchtype":"gaokao"//可选
    },
    "Method": "word_getnewswordlist",
    "Terminal": "2",
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": "202921"
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
            "word": "wallet",//单词
            "spell": "['wɔlit]",//拼写
            "mp3": "/mp3/3/2c7f5bf7c9a9e959d5122a462d5bdee9.mp3",//发音
            " meaning": "n. 皮夹，钱包",//解释
            "root": ""//注记
        },
        {
            "word": "negligence",
            "spell": "['neglidʒəns]",
            "mp3": "/mp3/13/28cb5feaeb012884b49d948864eb0a87.mp3",
            " meaning": "n. 疏忽，粗心大意",
            "root": "neg不+lig选择+ence表名词，“性质，状态”…不加选择…粗心→疏忽，粗心"
        },
        {
            "word": "figure",
            "spell": "['figə]",
            "mp3": "/mp3/3/29ff21d9996bc925ae8d870c32077b3a.mp3",
            " meaning": "n. 图形，数字，形状; 人物，外形，体型\nv. 演算，认为，领会到",
            "root": "fig做，制作+ure →做出的状态→形象，人物"
        }
    ],
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
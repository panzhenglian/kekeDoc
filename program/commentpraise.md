# 评论点赞
**JSON请求示例：**
```json	
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "type": 1, //1 表示节目评论，2 表示 文章评论 //必须
        "id": "6018" //评论id //必须
    },
    "Method": "v9_news_commentpraise",
    "Terminal": 3,
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 49 //必须
}
```
**JSON返回示例：**
```json
{
    "Code": 200,
    "Msg": "点赞成功",
    "Error": "",
    "Data": null,
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
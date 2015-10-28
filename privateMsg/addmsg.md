# 添加私信
**JSON 请求示例：**
```json
{
    "Token": "",
    "Params": {
        "username": "",//发送者姓名 可选
        "touid": "",//接收者id
        "typeflag": 0,//内容类型 0 表示文本，1 表示语音,2 表示图片
        "tousername": "zhouxy",//接受者姓名 
        "msg": "111",//发送内容
        "filename": "",// 文件扩展名，如果不传为音频
        "len": "0",//  音频长度
        "content": "" //语音 base64 内容 注意  
    },
    "Terminal": "0",//0为Pc/1为安卓/2为iphone/3为ipad/3为WP
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "Method": "msg_add",
    "UID": 49
}
```
**JSON返回示例：**
```json
{
    "Code": "200",
    "Error": "",
    "Data": {
        "uid": "49",
        "username": "",
        "touid": "",
        "typeflag": 1,
        "tousername": "zhouxy",
        "msg": "111",
        "terminal": "0",
        "dateline": "1431070619",
        "isread": 0,//0 未读，1 已读
        "len": 3,//语音大小
        "path": "/app/upload/15/05/08/49/1431070619.amr",//语音存储相对路径
        "mid": 36//信息id
    },
    "Token": ""
}
```
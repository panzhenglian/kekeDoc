# 加入小组
**JSON 请求示例：**
```json
{
    "Token": "",
    "Params": {
        "username": "aadf",
        "tagid": 18
    },
    "Method": "mtag_join",
    "Terminal": "1",
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 2189325
}
``` 
**JSON返回示例：**
```json
{
    "Code": 200,
    "Error": "",
    "Data": {
        "close": "0", //是否关闭0 是未关闭 1 代表关闭
        "joinperm": "0",
        "uid": "2189325",
        "tagid": "18",
        "threadsubject": "eee",//state 为1 的时候才有
        "threadtime":  "1429837812", //state 为1 的时候才有
        "state": "3"//0 代表 组不存在，1代表成功加入，2 代表 组组不公开，3 代表已经加入
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
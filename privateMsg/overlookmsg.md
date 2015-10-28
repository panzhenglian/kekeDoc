# 忽略信息
**JSON 请求示例：**
```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "touid": 1832536 //接收人id
    },
    "Method": "msg_overlookmsg",
    "Terminal": 3,
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 2080606
}
```
 
**JSON返回示例：**
```json
{
    "Code": 200,
    "Error": "",
    "Data": "", //如果有会返回消息id ，多个以逗号隔开
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
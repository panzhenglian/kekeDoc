# 动态点赞
**JSON 请求示例：**

```json
 {
    "Token": "3d89386cdf2f92c8b4f3f700262f5537",
    "Params": {
        "doid": 400288
    },
    "Method": "doing_praise",
    "Terminal": "1",
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 2182534
}
```
**JSON返回示例：**

```json
{
    "Code": 200,
    "Error": "repeat click ",
    "Data": {
        "status": "2" //表示已经送过了，1表示成功，0 表示失败
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
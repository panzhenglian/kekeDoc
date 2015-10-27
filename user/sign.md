# 每日打卡
JSON请求示例：  
```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": "",// 没有参数
    "Method": "customer_sign",
    "Terminal": 3, //0 为 pc，1为iphone,2为ipad,3为安卓，4为WP，5为QQ，6为新浪微博，7为微信
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 49
}
```

JSON返回示例：  
```json
{
    "Code": 200,
    "Error": "",
    "Data": {
        "num": 1, //返回连续打卡的次数
        "date": 1435939789
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
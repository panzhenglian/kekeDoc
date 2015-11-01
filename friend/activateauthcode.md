# 激活邀请码
> **注意Params 加密**

**JSON请求示例：**

```json
{
    "Token": "C4AD5BC8FE6BAE65640CCF6E51DFCC8E",
    "Params": {
        "authcode": "tENNfn2929415",//邀请码
        "appkey": "fn2929415fhhfhad"//ap端key （如果有机器码传机器码，如果没有机器码 就传 mac 码）
    },
    "Method": "friend_activateauthcode",
    "Terminal": 3,
    "Version": "2.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 2929415
} 
```
**JSON返回示例：**

```json
{
    "Code": 200,
    "Msg": "",
    "Error": "",
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
# 我的订单
**JSON请求示例：**

```json
{
    "Token": "fe95d19f1d8ccf8e4a2f5681b91dc87c",
    "Params": {
       "searchtype":1 //1 表示兑换订单，（扩展）
    },
    "Method": "customer_myorders",
    "Terminal": "2",
    "Version": "2.0",
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
            "title": 5元充值卡,
            "credits": 500，//扣除多少积分
	     "total":1000, //总积分
            "dateline":132843111,
            "status":1,//-1 代表失败，0 代表没有审核，1 代表通过
        },
      
    ],
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
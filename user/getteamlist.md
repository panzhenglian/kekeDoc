# 获取用户小组列表
**JSON请求示例：**
```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": {
        "PageIndex": 1,
        "PageSize": 1,
        "userid": 1832536
    },
    "Terminal": 3,
    "Version": "1.0",//1.0,2.0 通用
    "Lat": "100",
    "Lng": "444",
    "UID": 1832536,
    "Method": "customer_getteamlist"
}
```
**JSON返回示例:**
```json
{
    "Code": 200,
    "Msg": "成功",
    "Error": "",
    "Data": [
        {
            "tagid": "302",
            "tagname": "每日学口语",//组名
            "announcement": "每日一句，日积月累，练习口语",//描述
            "pic": "http://dipan.kekenet.com/attachment/group/2015/didaokouyu.jpg",//背景图
            "membernum": "5632",//人气
            "postnum": "22207",//帖子数
            "isjoin": "1"//是否加入， 0 未加入，1已经加入
        }
    ],
    "Token": "",
    "PageIndex": 1,
    "PageSize": 1,
    "PageCount":10,
    "IsDecode": 0,
    "Key": ""
}
```
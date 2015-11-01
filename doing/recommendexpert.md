# 推荐达人
**JSON 请求示例：**

```json
{
    "Token": "6ee729f6136db8c88306673478aec6ad",
    "Params": [],
    "Terminal": 3,
    "Version": "1.0",
    "Lat": "100",
    "Lng": "444",
    "UID": 163898,
    "Method": "doing_recommendexpert"
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
           "uid": "985415",
            "icon": "http://uc.kekenet.com/data/avatar/000/48/14/72_avatar_middle.jpg",//头像
            "username": "真的贞",//用户数量
            "doingcount": "3114”,//动态数
            "attentionflag": -1//-1表示未关注 ,0 表示单关注，1 表示相互关注，2表示取消关注,3 表示被取消关注

        },
        {
            "uid": "985417",
            "icon": "http://uc.kekenet.com/data/avatar/000/88/06/45_avatar_middle.jpg",
            "username": "午後的咖啡",
            "doingcount": "2901",
            "attentionflag": "1"
        }
    
    ],
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
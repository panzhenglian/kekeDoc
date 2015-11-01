# 添加测试句子
**JSON请求示例：**

```json
{
    "Method": "v9_news_addstudysentence",
    "UID": "2793192",
    "Version": "2.0",
    "Lat": "",
    "Lng": "",
    "Params": {
        "searchtype": 0,
        "seconds":1111，
        "sentenceinfoes": [
            {
       		 "id": 379492,//文章id
        	 "en": "A40-pagedossierhasbeenreleasedbytheUSJusticeDepartment", //英文
       		 "cn": "美国司法部公布了一份40页的文件，",//中文 //可选
      	        "rownum": 2,//句子在文章里顺序 2 代表第二句
               "catid": 15428,//课程id
               "wordnum": 1,//答对的单词数
               "minute": 1,//使用的分钟数
            }
        ]
    },
 
    "Token": "4EB5AE049AC0FA719B5D4843B953C784",
    "Terminal": 3
}
```

**JSON返回示例：**

```json
{
    "Code": 200,
    "Msg": "添加成功",
    "Error": "",
    "Data": {
   
    "credits": 100,
    "nextid": 1
    },
    "Token": "",
    "IsDecode": 0,
    "Key": ""
}
```
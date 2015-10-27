#文档概述
>手机客户端可以通过本接口获取所需数据  
>阅读对象：web服务器后台开发人员，app客户端开发人员

###接口环境
|类别     |说明  |备注
|:--------|:-----|:-------------|
| 请求协议 | http |默认开启GZIP   |
| 请求方式 | post |字符编码方式UTF8|
| 返回方式 | json |字符编码方式UTF8|
###接口形式
1. 所有的业务操作请求形式如下:
```
http://{host}:{port}/mobile/index.php
host为提供服务的主机ip或域名,
port为服务的端口号
version为接口版本号，目前版本为1.0
```	 
2. 请求参数置于http message body, message body采用utf8编码方式, message body 采用json数据格式,格式如下:
```json
{ 
      "Token": "3d89386cdf2f92c8b4f3f700262f5537",//安全凭证(可选)
      "Params": {
	        "Mobile": "123456"
      },
      Method:"Customer_Register"，
      "Terminal": "2",// 0为Pc/1为安卓/2为iphone/3为ipad/3为WP(可选)
      "Version": "1", 版本1代表1.0 目前为服务端为1.0 (可选)
      "Lat": "100",  //用户地理位置经度
      "Lng": "444",  //用户地理位置纬度
      "Uid": 12  //用户登录后ID
}	
```

3. 服务端响应参数置于http message body, message body 采用json数据格式,格式如下:
```json
{
		"Code": 200, //定义请求处理后的结果状态码,200表示成功
		"Msg": "",//定义请求处理出错时的提示消息,用于在移动客户端显示
		"Data":{},//给终端数据
		"PageIndex": 1, // 页码 只有列表页面才有
		"PageSize": 20,//页码大小  只有列表页面才有
		"PageCount": 10,//总页数 只有列表页面才有
		"Token": "123454"//安全凭证(可选)
}
```



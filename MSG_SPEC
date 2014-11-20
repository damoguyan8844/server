# 消息格式定义

消息以json编码，分为用户消息和系统消息两类


# 消息字段定义

- 发送者

	字段名: user_name

	字段取值: 发送者标识

- 消息类型

	字段名: type

	字段取值:

		1: 用户消息 

		2: 系统消息

- 消息内容类型

	字段名: sub_type

	字段取值:

		1: 文本消息

		2: 音频消息

		3: 视频消息

- 消息内容

	字段名: content

	字段取值:

	当 sub_type = 1时， 内容为普通文本
	
	当 sub_type = 2 或 3 时， 内容为音、视频 url


# 消息示例：

* 文本消息

````
{
	"user_name": "decker",
	"type": 1，
	"sub_type": 1
	"content": "hello"
}

````

* 音频\视频消息

````
{
	"user_name": "decker",
	"type": 1，
	"sub_type": 2
	"content": "http://horcus/hello.mp3"
}


````


* 系统消息

````
{
	"user_name": "decker",
	"type": 2，
	"sub_type": 1
	"content": "hello"
}

````

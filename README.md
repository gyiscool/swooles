# swoole websocket通信
主要实现以下功能

功能一：
  后台推送一个组的通知
功能二：
  实时聊天
----
json参数示例

握手阶段：
根据get参数判断接口权限

发送消息时候
{"data":"消息信息","to":[1,2,3]}
from 表示我的加密的 包含我的uid 包含一个判断(不允许前台发送通知)
data 发送的内容
to表示发送人的uid是数组 发送循环



吐tm个槽
什么jb文档 都不敢写类了的，一个连接实例化一个

算了，加密写在一个类吧
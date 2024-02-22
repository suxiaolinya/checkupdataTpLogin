# suTpLogin
## 功能
* 1.当玩家加入服务器时传送到固定的坐标
* 2.拥有指定权限的玩家可以上线到权限地点
* 3.当玩家掉入虚空时自动传回固定的坐标
## 指令&权限
* /tl set---tplogin.tl---默认op-设置固定坐标
* /tl set [权限]---tplogin.tl---默认op-设置权限上线点
* /tl reload ---tplogin.tl---默认op-重载配置文件
## 使用教程
* 站到你想设置的点，面对你想面对的方向\n
* 然后输入/tl set
* 权限点的设置
* 站在你想设置的点，面对你想面对的方向
* /tl set [权限]
* 即可设置
### 例子:
* /tl set admin
* 拥有权限tplogin.admin的玩家上线会传送的该权限的传送点
## 配置文件
* 可以设置是否启用检查更新
* 可以设置是否启用掉入虚空传送回上线点
* 当设置完传送点后会多出location项
* 如果设置权限上线点会多出permission项
* 如果需删除权限上线点请进入配置文件删除对应的权限下包括的所有内容
* 然后/tl reload


![统计信息](https://bstats.org/signatures/bukkit/suTpLogin.svg)

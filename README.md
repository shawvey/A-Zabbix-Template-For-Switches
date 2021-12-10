# A-Zabbix-Template-For-Ruijie-Switches
一个所有交换机类型均可通用的zabbix模板，模板包含以下监控项：
1、ifType 接口的类型 取值117表示接口为GigabitEthernet取值62表示借口为FastEnthernet
2、ifDescr 接口类型的描述 有GigabitEthernet、FastEthernet等
3、ifinOctets 接口输入的字节数
4、ifoutOctets 接口输出的字节数
5、ifSpeed 接口速率
6、ifPhysAddress  接口的数据链路地址
7、ifAdminStatus  接口的管理状态
8、ifOperStatus 接口的操作状态
9、ifLastChange 接口最后更新成当前操作状态的时刻
10、ifInUcastPkts 通过上层协议传递到子网的单播报文数
11、ifInNUcastPkts 传递给上层网络协议的非单播报文数
12、ifInDiscards 被丢弃（尽管没有错误）的输入报文数，并且这些报文不会被传递给上层网络协议
13、ifInErrors 流入的错误报文数，由于错误使得这些报文不会被传递给上层网络协议
14、ifInUnknownProtos 由于未知或不支持的网络协议而丢弃的输入报文的数量
15、ifOutUcastPkts 上层协议（如IP）需要发送给一个网络单播地址的报文数，该数量包括丢弃的或未发送的报文数
16、ifOutNUcastPkts 上层协议（如IP）需要发送给一个非单播地址的报文数，该数量包括丢弃的或因为某种原因未发送的报文数
17、ifOutErrors 由于错误而不能发送的报文数量
18、atIfIndex 指向每个特定映射
19、atPhysAddress 介质相关的物理地址（是一个有效的IP地址）
20、atNetAddress 介质相关物理地址所关联的IP地址


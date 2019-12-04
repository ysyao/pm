# 网络标准与网络协议

网络协议是为计算机网络中进行数据交换而建立的规则、标准或约定的集合。网络协议由三个要素组成，分别是**语义、语法和时序**。语义表示要做什么，语法表示怎么做，时序表示做的顺序。

## OSI协议

ISO和CCITT联合指定的开放系统互联参考模型（OSI），采用了分层的结构化技术从上到下共分七层。

* 物理层：RS232、V.35、RJ-45、FDDI。
* 链路层：IEEE 802.3/.2、HDLC、PPP、ATM。
* 网络层：IP、ICMP、IGMP、IPX、ARP。
* 传输层：TCP、UDP、SPX。
* 会话层：RPC、SQL、NFS。
* 表示层：JPEG、ASCII、GIF、DES、MPEG。
* 应用层：HTTP、Telnet、FTP、SMTP。

> 具体网络协议的内容参考[阮一峰《互联网协议入门》](https://www.ruanyifeng.com/blog/2012/05/internet_protocol_suite_part_i.html)

## 网络协议和标准

以太网规范IEEE802.3是重要的局域网协议，包括：

* IEEE802.3   标准以太网 10Mb/s    传输介质为细同轴电缆
* IEEE802.3u 快速以太网 100Mb/s  双绞线
* IEEE802.3z 千兆以太网 1000Mb/s 光纤或双绞线

## TCP/IP

TCP/IP协议是Internet的核心。

### 应用层协议

主要有FTP、TFTP、HTTP、SMTP、DHCP、Telnet、DNS、SNMP。

### 传输层协议

主要有TCP和UDP。

### 网络层协议

主要有IP、ICMP、IGMP、ARP、RARP。


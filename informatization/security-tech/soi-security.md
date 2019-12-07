# 信息系统安全

信息系统安全主要包括**计算机设备安全、网络安全、操作系统安全、数据库安全和应用系统安全**等。

## 计算机设备安全

计算机设备安全的**关键因素**包括**机密性、完整性、可用性、抗否认性、可审计性、可靠性**。

* 私密性：信息不被未授权者知晓的属性。
* 完整性：信息是正确的、真是的、未被篡改的、完整无缺的属性。
* 可用性：信息可以随时正常使用的属性。
* 抗否认性：保障用户无法在事后否认曾经对信息进行的生成、签发、接受等行为的特征。主要靠数字签名。
* 可审计性：利用审计方法，可以对计算机信息系统的工作过程进行详尽的审计跟踪，同时保存审计记录和审计日志。
* 可靠性：计算机设备的可靠性是指计算机在规定的条件下和给定的时间内完成预定功能的概率。影响计算机可靠性因素中，元器件是基础，设计是关键，环境是保证。要提高可靠性还要采用容错技术（增加冗余资源的办法）和故障诊断技术（通过检测和排除系统元器件，或线路故障或纠正程序的错误）。

计算机设备安全包括：

1. 物理安全：场地安全、环境安全，主要是场地和机房安全。
2. 设备安全：设备防盗和防毁，防止电磁信息泄露。
3. 存储介质安全：介质本身和介质上存储数据的安全。
4. 可靠性技术：一般采用容错系统实现，容错主要依靠冗余设计来实现。冗余技术可以分为硬件冗余、软件冗余、时间冗余和信息冗余。

## 网络安全

互联网（Internet）的安全问题：

1. 信息泄露、信息污染、信息不易受控。
2. 信息泄密、信息破坏、信息授权和信息渗透。
3. 网站遭受恶意攻击而导致损坏和瘫痪。

Internet基于TCP/IP协议，常见的网络威胁：

1. 网络监听。
2. 口令攻击。
3. 拒绝服务攻击（Dos）。
4. 漏洞攻击。
5. 僵尸网络（Botnet）。
6. 网络钓鱼（Phishing）。
7. 网络欺骗，ARP欺骗、DNS欺骗、IP欺骗、Web欺骗、Email欺骗。
8. 网络安全威胁，SQL注入攻击、跨站攻击、旁注攻击等。

网络安全防御技术：

1. 防火墙。
2. 入侵检测与防护：主要技术有入侵检测系统（**IDS**）和入侵防护系统（**IPS**）。IDS注重网络安全状况的监管，通过监视网络或系统资源，寻找违反安全策略的行为或攻击迹象；IPS提供主动防御，预先对入侵活动和攻击性网络流量进行拦截。 

> IDS是出事了报警，IPS是预判拦截。

3. VPN：使用”隧道“的技术作为传输介质。常见的点对点隧道协议（PPTP）、第二层隧道协议（L2TP）和IP安全协议（IPSec）。
4. 安全扫描：漏洞扫描、端口扫描、密码类扫描等。
5. 网络蜜罐技术：诱骗系统。

## 操作系统安全

其安全威胁按照行为方式划分：

1. 切断，对可用性威胁。
2. 截取，对机密性威胁。
3. 篡改，对完整性威胁。
4. 伪造，对合法性威胁。

按照表现形式划分：

1. 计算机病毒。
2. 逻辑炸弹。
3. 特洛伊木马。
4. 后门。
5. 隐蔽通道。

操作系统安全性具体包括：

1. 身份认证机制。
2. 访问控制机制。
3. 数据保密性。
4. 数据完整性。
5. 系统的可用性。
6. 审计。

## 数据库系统安全

数据库系统安全设计以下问题：

1. 物理数据库的完整性：不因自然或者物理因素被破坏。
2. 逻辑数据库的完整性：数据库系统结构、模式、数据不被非法修改。
3. 元素安全性：各种存储元素满足机密性、完整性、可用性。
4. 可审计性。
5. 访问控制。
6. 身份认证。
7. 可用性：对授权用户有高质量数据访问服务。
8. 推理控制：保证用户不能从被公开发布的、授权可被访问的信息中推导出机密的、未被授权访问的信息。
9. 多级保护：划分保密等级。

数据库安全办法：

1. 访问控制技术。
2. 数据库加密技术。
3. 多级安全数据库技术。
4. 数据库的推力控制问题。
5. 数据库的备份与恢复。

## 应用系统安全

面临威胁：可信任站点的漏洞；浏览器和浏览器插件的漏洞；终端用户的安全策略不健全；携带恶意软件的移动存储设备；网络钓鱼；僵尸网络；带有键盘记录程序的木马等。

防护技术：

1. Web访问控制技术。
2. 单点登录（SSO）技术。
3. 网页防篡改技术。
4. Web内容安全。

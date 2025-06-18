# 贡献者

# 关于作者

**卡尔·莱恩**是 AT&T/LevelBlue 的**安全运营中心**（**SOC**）团队负责人，通过承包商 Pinnacle Group 支持德克萨斯州。他领导着一个由中年网络安全分析师组成的团队，保护着多个网络安全环境中的多个机构。卡尔持有认证的道德黑客（CEH）和网络安全分析师（CySA+）认证，涵盖了进攻性和防御性安全。他是教育和培训的坚定支持者，主张通过实践经验和个人指导来学习。

卡尔的技术之旅始于 1990 年代末至 2000 年代初，他在美国陆军服役期间。当时，他驻扎在比利时布鲁塞尔的北约总部，他的一位同事欣赏他的写作风格，并邀请他帮助创建一个基于文本的游戏内容。为此，他需要学习如何使用 Linux 操作系统，以及如何用传统的 C 语言编写代码。这促使他在完成军事服役后攻读信息技术本科专业。在学习过程中，他获得了 3M 公司全球总部的一项技术辅助职位，3M 是一家位于明尼苏达州圣保罗的跨国创新公司。正是在那里，他通过软件测试学会了*破坏事物*，这引导他走上了应用渗透测试，最终进入了网络安全行业。

目前，卡尔与妻子 Britni 以及不断变化的养育孩子的数量住在佛罗里达州的迪士尼世界附近，因为他们是寄养父母。

重复是所有学习的母亲，实践应用是父亲。参考资料是很好的学习支持，但不能替代学习过程。灌输式学习并非真正的学习。

# 关于审阅者

**乔·克雷默**自 2016 年起从事网络安全工作，目前是 The Judge Group 和 LevelBlue 的三级安全分析师，支持 200 多个州级机构的网络安全需求。他曾在 22 世纪技术公司担任武器和战术分析师及助理项目经理，在那里他学习、操作并教授了如 BlueCoat、Paloalto、Fidelis、TippingPoint、Niksun、Elastic、Splunk、ArcSight、Devo、McAfee、Remedy、ServiceNow 等工具，以及各种定制的应用程序。在进入民间生活之前，乔在美国海军服役九年，担任密码技术员，操作全球规模的传感器网络，为舰队和国家客户提供相关的时间敏感报告。

**Deepanshu Khanna** 是一位受到印度国防、印度政府、内政部、警察部门以及众多全球知名 IT 公司、杂志、报纸等机构赞赏的黑客。他通过在 HATCon 展示一项著名的 GRUB 漏洞研究开始了他的职业生涯，并且他在 IDS、AIDE 领域的研究成果，包括实际展示 MD5 碰撞、缓冲区溢出等内容，发表在了多本杂志上，如 PenTest、Hackin9、eForensics、SD Journal、Hacker5 等。他受邀参加了 DEF CON、ToorCon、OWASP、HATCon、H1hackz 等多个公开会议，以及许多大学和研究机构，担任嘉宾讲者。

# 目录

## 前言

## 第一部分：介绍、历史与安装

## 1

## 网络安全入门

### 我们是如何走到这一步的

### Stuxnet

### 2013 年 Target 网络攻击

### 攻击性安全

### Nmap

### Metasploit 框架

### Burp Suite

### Wireshark

### Aircrack -ng

### John the Ripper

### Hydra

### SQLmap

### Maltego

### 社会工程学工具包 (SET)

### 防御性安全

### 保密性

### 完整性

### 可用性

### 总结

### 问题

### 进一步阅读

## 2

## Kali Linux 与 ELK 堆栈

### Kali Linux 的发展历程

### Elasticsearch、Logstash 和 Kibana (ELK 堆栈)

### Elasticsearch

### Logstash

### Kibana

### 代理和监控

### Beats

### X-Pack

### 总结

### 问题

### 进一步阅读

## 3

## 安装 Kali Purple Linux 环境

### 技术要求

### 获取 Kali Purple 发行版

### Linux 备份

### Windows 备份

### macOS 备份

### Linux

### Mac

### Windows

### 虚拟机的安装

### Windows 用户

### macOS 用户

### Linux 用户

### Linux VirtualBox 安装

### macOS VirtualBox 安装

### Windows VirtualBox 安装

### 设置 Windows 环境 PATH 变量

### 设置 macOS 或 Linux 环境 PATH 变量

### Kali Purple 的安装

### Java SDK 的安装

### 总结

### 问题

### 进一步阅读

## 4

## 配置 ELK 栈

### 技术要求

### Elasticsearch

### Kibana

### Logstash

### 总结

### 问题

### 进一步阅读

## 5

## 向 ELK 栈发送数据

### 技术要求

### 理解数据流

### Filebeat

### Linux 和 macOS 的下载与安装

### Beats 类型

### Elastic Agent

### Logstash 与过滤器

### 总结

### 问题

### 进一步阅读

## 第二部分：数据分析、筛选与事件响应

## 6

## 流量与日志分析

### 技术要求

### 理解数据包

### Malcolm

### Arkime

### CyberChef 与混淆

### 总结

### 问题

### 进一步阅读

## 7

## 入侵检测与防御系统

### 技术要求

### IDS

### 流量监控

### 异常检测

### 基于签名的检测

### 实时警报

### 日志与事件分析

### 基于网络与主机的检测

### 响应与缓解

### 合规性

### 与安全基础设施的集成

### IPS

### 实时威胁防护

### 自动响应

### 策略执行

### 内联保护

### 应用层保护

### 性能优化

### Suricata

### Zeek

### 总结

### 问题

### 进一步阅读

## 8

## 安全事件与响应

### 技术要求

### 事件响应

### Docker

### Cortex

### TheHive

### 挑战！

### 总结

### 问题

### 进一步阅读

## 第三部分：数字取证、进攻性安全与 NIST CSF

## 9

## 数字取证

### 技术要求

### 数字取证与恶意软件分析

### 可执行文件标识符 (PEiD)

### PEScan

### IDA Pro

### Volatility3

### ApateDNS

### SET

### BeEF

### Maltego

### 总结

### 进一步阅读

## 10

## 集成红队与外部工具

### 技术要求

### OWASP ZAP

### Mozilla Firefox

### Google Chrome

### Wireshark

### Metasploit

### 扫描器

### Nmap

### SQLmap

### Nikto

### Nessus

### Greenbone 漏洞管理与 OpenVAS

### 密码破解

### Hydra

### Medusa

### John the Ripper

### Burp Suite 集成

### 总结

### 问题

### 进一步阅读

## 11

## 自动驾驶仪、Python 和 NIST 控制

### 技术要求

### 自动驾驶仪

### Python

### NIST 控制

### 识别

### 保护

### 检测

### 响应

### 恢复

### 管理

### 总结

### 问题

### 进一步阅读

## 附录：答案键

## 索引

## 你可能喜欢的其他书籍

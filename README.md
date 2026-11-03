# Cybersecurity-Project

Design and Implementation of a Traffic Feature-Based DDoS Anomaly Detection and Alerting System
=基於流量特徵的DDoS異常偵測與警報系統的設計與實現
=分别DDos流量有特别大和正常流量区分，以非正常流量进行警报

DDos攻击server DDos攻击自己电脑 防御DDos异常流量

限流

对比工具，进行优化
准确性，

使用3个常用的DDos检测工具-- Suricata, webnetwork, FastNetMon
Suricata--https://www.cnblogs.com/smileleooo/p/18169413
https://github.com/oisf/suricata
可进行TCP, UDP, ICMP, HTTP, FTP等，可进行已知攻击模式，同时检测应用层的攻击和异常行为 例如SQL注入
并不能检测到干净IP的UDP flooding，因为没有流量统计异常检测能力

FastNetMon--专为大流量设计
long latency

webnetwork--零门槛,自动封禁恶意 IP,实时抓包（TCP/SYN）
功能极其基础,仅包含SYN Flood

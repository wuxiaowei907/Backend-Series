# 自动化运维

随着分布式系统愈加成熟，应用的规模越来越大，系统构成也越来越复杂，服务器的数量迅速地从几十台、上百台增加到成千上万台。企业内部服务器数量的大幅增长，使得服务器出现故障的频次也大幅增加，手工运维时代的瓶颈随之到来。

运维工程师越来越难以远程登录每一台服务器去搭建环境、部署应用、清理磁盘、查看服务器状态以及排查系统错误，此时急需自动化运维体系与开发技术体系配合。自动化运维工具主要包括两大类：监控自动化工具以及流程自动化工具。

监控自动化工具可以对服务器的 CPU、内存、磁盘 IO、网络 IO 等重要配置进行主动探测监控，一旦指标超过或接近阈值则自动通过邮件、短信等方式通知相关责任人。使用 Nagios、Zabbix 等系统监控工具可以有效实现这一点。

流程自动化工具主要对服务器进行维护，同时实现应用上线部署等日常操作的自动化和标准化。Puppet、Chef、Ansible、SaltStack 等自动化运维管理工具的出现，快速地将运维工作推向自动化，让一名运维工程师可以很容易地维护成千上万台服务器。

# 关于CentOS官方停止维护CentOS Linux8的应对方案

依据CentOS官方公告所知，其将停止维护CentOS Linux8项目，UCloud所提供的基础镜像CentOS Linux8源于CentOS官方，故在官方停止维护后UCloud也将停止对该基础镜像的维护。
本文主要就CentOS官方公告内容及影响，UCloud基础镜像应对方案及应对建议进行介绍。



## CentOS官方公告内容
2020年12月08日，CentOS官方宣布了停止维护CentOS Linux 8的计划，并推出了CentOS Stream项目。具体信息，请阅读CentOS官方公告。其具体规划如下：
- CentOS Linux 8作为RHEL 8的复刻版本，生命周期缩短，于2021年12月31日停止更新并停止维护（EOL）。
<br>
基于以上官方变更计划，CentOS Linux 8用户将无法获得包括问题修复和功能更新在内的任何软件维护和支持。CentOS官方建议停止维护后：对于开发或测试环境，可以将环境迁移至CentOS Stream版本；
对于生产环境或部署关键业务的系统，建议使用稳定的Red Hat Enterprise Linux。对此，用户需评估以下问题：

- CentOS Stream是一个滚动发行的版本，仅为RHEL前置测试版，运用于生产环境时，可能存在一定风险。
<br>


## UCloud基础镜像应对方案
基于CentOS官方将停止对CentOS Linux8停止更新和维护，UCloud的应对方案如下：
- UCloud将停止对该基础镜像的更新和维护，但对于正在使用CentOS Linux8的云主机用户不会有任何影响；
- UCloud将提供Rocky Linux镜像。
<br>

关于Rocky Linux镜像 <br>
Rocky Linux 是一个社区化的企业级操作系统。Rocky Linux 由 CentOS 项目的创始人 Gregory Kurtzer 领导，旨在打造兼容Red Hat且稳定的Linux操作系统，延续CentOS稳定Linux发行版路线。<br>
目前，UCloud已支持部分客户测试使用Rocky Linux镜像（有意测试的用户请咨询技术支持），并计划在2022年1月，作为基础镜像上线控制台。
<br>


## 应对建议
UCloud基础镜像中还提供了其他多种基础镜像可选，您可以根据业务的实际情况，选择适用的操作系统替代CentOS Linux8。具体说明如下：

| 镜像名称 | 概述 |
| ----------- | ---------|
|Red Hat Enterprise Linux | Red Hat Enterprise Linux是Red Hat公司提供的企业版操作系统，UCloud基础镜像中目前支持RedHat 8.3 64位版本。|
|Rocky Linux  | Rocky Linux 是一个社区化的企业级操作系统，Rocky Linux与CentOS一样，提供了适用于服务器的稳定版本，旨在作为CentOS完全兼容的替代版本。 |
|Debian、Ubuntu等其他操作系统 | Linux的其他发行版操作系统，不同操作系统在使用习惯和应用兼容性上存在一定差异。|

# 服务器安全运维规范（Server security operation）


## 项目简介
项目主要是汇集整理服务器安全运维规范，包括运维工程师必须遵守的规范、服务器运维中注意事项、故障避免手段等文档，帮助运维工程师避免服务器安全和运维故障，方便运维工程师学习成长。


### 现状
目前，网上运维工程师服务器安全意识参差不齐，大部分都存在这三方面的问题：
- 服务器安全不是很懂；
- 服务器安全重要，但没按要求做，或安全设置不全面；
- 服务器安全重要，安全设置都有做，但实际操作有遗忘，安全意识不强。

比如：在2017/01/31 18:00 UTC国外Gitlab出现故障，丢失了6小时的生产数据！Gitlab 数据库终于在北京时间 2月2日 0:14 恢复成功（18:14 UTC 02/01）。运维工程师操作时。没有检查正在操作的服务器，以至于误删除了正常的数据。

## 服务器安全那些要做，那些不要做
安全设置要不要做？做安全还是不做安全？还是说只做一些基础设置。
如果安全相关工作，能让服务器和服务器集群更安全，那就要去做。
安全的相关工作尽量做，不会做的想办法做，实在没法做的，那就延后再说。
安全无小事，要想想不安全的后果，如果出现安全事件，数据泄露，数据库被拖库，后果是很严重的，这样的案例互联网上很多，就不多说了。

项目的口号是：使用服务器安全运维规范，不掉坑，不背锅！

## 一起来参与，补充服务器安全运维规范
- 如果想要贡献或是交流的话，请加 QQ 群： 7652650 （安全运维）
- Email：ppabc@qq.com


## 适合的职业
- 运维工程师
- 运维经理
- 运维总监
- 资深运维工程师
- 安全运维工程师
- 运维开发工程师
- 安全工程师


## 说明
### 关于重要程度标签
- 重要程度：R1-R5, 对应关系：基础(R1)、简单(R2)、一般(R3)、重要(R4)、非常重要(R5)
建议：R3以上，运维工程师必须做到！做到的好处是：可以避免一些业务故障和安全事件！


## 项目进度
- 2017年2月2日，正式起草。
- 2017年2月8日，第一个版本。

## 鸣谢


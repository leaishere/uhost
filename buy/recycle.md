# 回收/删除

!> 回收或删除后的资源很难被找回，还请您及时续费及备份数据，如有特殊情况，请提交工单，我们将尽力为您找回。

## 通知渠道

所有通知消息将通过邮件、短信以及站内信的方式通知到您设置的通知接收人。

设置通知人：<https://console.ucloud.cn/umon/contact>

## 回收
### 预付费按年付/按月付

当前计费模式下云主机的回收及通知流程见下图所示：

![](/images/buy/recycle1.png)

当您的资源过期前3天：给您设置的通知接收人发送资源即将过期预警；

当您的资源过期当天：给您设置的通知接收人发送资源已过期通知；

当您的资源过期后3天：给您设置的通知接收人发送云主机即将被关机提醒，当天对云主机执行关机操作，关机后的云主机需先完成续费方可开机继续使用；

当您的资源过期后10天：给您设置的通知接收人发送云主机即将被回收提醒，当天对云主机执行回收操作（回收后的资源不可找回，还请及时续费）。

### 预付费按小时付

![](/images/buy/recycle2.png)

当您的资源过期后当天：发送已过期提醒；

当您的资源过期第1天：发送资源即将被回收通知；

当您的资源过期后第2天：发送回收通知，并回收主机。

### 后付费按小时付

按时后付费云主机每小时生成一张后付费订单，若您的账户可用余额充足，将自动扣费，若您的账户可用余额不足支持扣费，将产生欠费订单；

累计3张后付费欠费订单：发送资源可能被回收通知；

累计3张后付费欠费订单+24H：发送资源停机通知，且当天系统强制停机；

累计3张后付费欠费订单+48H:发生资源删除通知，且当天回收资源。


## 删除

如果您在资源有效期内删除资源，系统将会根据您的付费方式分别计算的您的账单信息。
您在删除主机时，该资源挂载的云盘、网络等资源也将同步被删除释放。

### 预付费

如果您选择的主机为预付费模式（包括按年付、按月付、按小时支付），如果您在有效期内删除资源，则系统将根据您的使用时长扣除费用，退还剩余的预付金额至您的账户，具体退费规则见[删除资源退费](https://docs.ucloud.cn/charge/refund)。

### 后付费

如果您选择的主机为后付费模式，当您删除该主机，则系统将在停止该资源的服务，并在整点时为您生成需付费订单。<br>

> 1. 在预付费模式下，如果您在删除主机时，当前使用时长非完整的小时数，系统将自动补足一个小时，系统根据实际用量计算应退费金额。<br>
> 2. 如您需要了解详细的退费规则，请阅读[删除资源退费](https://docs.ucloud.cn/charge/refund)。<br>




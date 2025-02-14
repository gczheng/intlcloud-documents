### 操作场景
腾讯轻联告警配置提供查看告警历史功能，以便您回溯和查看近一个月的告警历史记录。您也可以在告警历史页快速查看告警策略。

## 操作步骤

### 查看告警历史

1. 登录腾讯轻联控制台，进入**告警配置** > [**告警历史**](https://ipaas.tencentcloud.com/login) 页面。
2. 单击左上角的“时间筛选”，筛选需要查看告警历史的时间范围。
   支持近5分钟、近15分钟、近30分钟、近1小时、近6小时、近1天、昨天、近7天、近30天快速筛选，您也可以自定义时间范围。最多可查看近一个月的告警历史。
3. 您可以在“告警对象”搜索框中输入告警对象的信息搜索对应的历史记录，例如：应用名称。
4. 还可以根据 [告警状态](#state)、告警类型、告警级别、策略名称、环境等筛选出符合条件的告警历史记录。
   ![](https://qcloudimg.tencent-cloud.cn/raw/2affbdfc1403182909b8541f81ac8988.png)

### 重置筛选条件

您成功筛选告警历史信息后，在列表中单击**重置**即可。
![](https://staticintl.cloudcachetci.com/yehe/backend-news/k8fR055_f08546b75ce22a3746c2f0d719462a09.png)

[](id:state)
## 告警状态
<table>
<tbody>
<tr>
<th width="15%">告警状态</th>
<th width="85%">说明</th>
</tr>
<tr>
<td>持续中</td>
<td>没有被处理或正在被处理的告警</td>
</tr>
<tr>
<td>已恢复</td>
<td> 已经恢复正常状态</td>
</tr>
<tr>
<td>已失效
</td><td> 告警策略被删除等异常情况
</td></tr>
</tbody></table>

# 查看实例<a name="dms-ug-180604014"></a>

## 操作场景<a name="section21574462"></a>

本节介绍如何在分布式消息服务管理控制台查看Kafka专享版实例的详细信息。

## 前提条件<a name="section59952436"></a>

已成功申请Kafka专享版实例。

## 操作步骤<a name="section1860982374010"></a>

1.  登录管理控制台。
2.  在管理控制台左上角单击![](figures/icon-region.png)，选择区域。

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >此处请选择与租户的应用服务相同的区域。  

3.  单击页面上方的“服务列表”，选择“应用服务 \> 分布式消息服务”，进入分布式消息服务信息页面。
4.  单击左侧菜单栏的“Kafka专享版”。
5.  Kafka专享版实例支持通过筛选来查询对应的Kafka专享版实例。当前支持的筛选条件为“状态”和“名称”。Kafka专享版实例状态请参见[表1](#table5086721717534)。

    **表 1**  Kafka专享版实例状态说明

    <a name="table5086721717534"></a>
    <table><thead align="left"><tr id="row4878914717534"><th class="cellrowborder" valign="top" width="17%" id="mcps1.2.3.1.1"><p id="p50270420175321"><a name="p50270420175321"></a><a name="p50270420175321"></a>状态</p>
    </th>
    <th class="cellrowborder" valign="top" width="83%" id="mcps1.2.3.1.2"><p id="p51272037175321"><a name="p51272037175321"></a><a name="p51272037175321"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row4409498617534"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p5195001718130"><a name="p5195001718130"></a><a name="p5195001718130"></a>创建中</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p6525251518130"><a name="p6525251518130"></a><a name="p6525251518130"></a>申请Kafka专享版实例后，在Kafka专享版实例状态进入运行中之前的状态。</p>
    </td>
    </tr>
    <tr id="row4964581717534"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p3431187918130"><a name="p3431187918130"></a><a name="p3431187918130"></a>运行中</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p3711473418130"><a name="p3711473418130"></a><a name="p3711473418130"></a>Kafka专享版实例正常运行状态。</p>
    <p id="p6559715218130"><a name="p6559715218130"></a><a name="p6559715218130"></a>在这个状态的实例可以运行您的业务。</p>
    </td>
    </tr>
    <tr id="row8089014121228"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p1022935121239"><a name="p1022935121239"></a><a name="p1022935121239"></a>故障</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p593735121239"><a name="p593735121239"></a><a name="p593735121239"></a>Kafka专享版实例处于故障的状态。</p>
    </td>
    </tr>
    <tr id="row23496423121248"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p549840112131"><a name="p549840112131"></a><a name="p549840112131"></a>启动中</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p3755454112131"><a name="p3755454112131"></a><a name="p3755454112131"></a>Kafka专享版实例从已关闭到运行中的中间状态。</p>
    </td>
    </tr>
    <tr id="row5150934512136"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p43939024121312"><a name="p43939024121312"></a><a name="p43939024121312"></a>重启中</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p51371030121312"><a name="p51371030121312"></a><a name="p51371030121312"></a>Kafka专享版实例正在进行重启操作。</p>
    </td>
    </tr>
    <tr id="row2402314317534"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p3881314218130"><a name="p3881314218130"></a><a name="p3881314218130"></a>正在关闭</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p4199865618130"><a name="p4199865618130"></a><a name="p4199865618130"></a>Kafka专享版实例从运行中到已关闭的中间状态。</p>
    </td>
    </tr>
    <tr id="row1102564917534"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p2070814618130"><a name="p2070814618130"></a><a name="p2070814618130"></a>已关闭</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p3780836018130"><a name="p3780836018130"></a><a name="p3780836018130"></a>Kafka专享版实例被正常停止。</p>
    <p id="p473092718130"><a name="p473092718130"></a><a name="p473092718130"></a>在这个状态下的实例，不能对外提供业务。</p>
    </td>
    </tr>
    <tr id="row224215391011"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p724310331011"><a name="p724310331011"></a><a name="p724310331011"></a>已冻结</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p122431831109"><a name="p122431831109"></a><a name="p122431831109"></a>Kafka专享版实例处于已冻结状态，用户可以在“我的订单”中续费开启冻结的Kafka专享版实例。</p>
    </td>
    </tr>
    </tbody>
    </table>

6.  单击Kafka专享版实例的名称，进入该Kafka专享版实例的基本信息页面，查看Kafka专享版实例的详细信息。


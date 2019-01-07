# Kafka实例创建Topic<a name="dms-ug-180604018"></a>

创建Kafka专享版实例成功后，可以在Kafka专享版实例中创建Topic。

## 前提条件<a name="section11712186286"></a>

已创建Kafka专享版实例。

只有运行中的实例才可以创建Topic。

## 操作步骤<a name="section0249155910409"></a>

1.  登录管理控制台。
2.  在管理控制台左上角单击![](figures/icon-region.png)，选择区域。

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >此处请选择与租户的应用服务相同的区域。  

3.  单击页面上方的“服务列表”，选择“应用服务 \> 分布式消息服务”，进入分布式消息服务信息页面。
4.  单击左侧菜单栏的“Kafka专享版”。
5.  在“Kafka专享版”页面，单击Kafka专享版实例的名称。

    进入实例详情页面。

6.  选择“Topic管理”页签，单击“创建Topic”。

    弹出“创建Topic”的窗口。

7.  填写Topic名称和配置信息。

    **表 1**  Topic参数说明

    <a name="table186364410350"></a>
    <table><thead align="left"><tr id="row66474473513"><th class="cellrowborder" valign="top" width="23%" id="mcps1.2.3.1.1"><p id="p7641944173520"><a name="p7641944173520"></a><a name="p7641944173520"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="77%" id="mcps1.2.3.1.2"><p id="p264154419353"><a name="p264154419353"></a><a name="p264154419353"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row8641444183514"><td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.3.1.1 "><p id="p12649444358"><a name="p12649444358"></a><a name="p12649444358"></a>Topic名称</p>
    </td>
    <td class="cellrowborder" valign="top" width="77%" headers="mcps1.2.3.1.2 "><p id="p886312445210"><a name="p886312445210"></a><a name="p886312445210"></a>DMS为您自动生成了Topic名称，您可以根据需要修改，Topic名称只能包含a~z，A~Z，0-9，-，_，长度为4~64的字符串。</p>
    <p id="p19863142405214"><a name="p19863142405214"></a><a name="p19863142405214"></a>创建Topic后不能修改名称。</p>
    </td>
    </tr>
    <tr id="row196494414358"><td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.3.1.1 "><p id="p10641644103512"><a name="p10641644103512"></a><a name="p10641644103512"></a>分区数</p>
    </td>
    <td class="cellrowborder" valign="top" width="77%" headers="mcps1.2.3.1.2 "><p id="p1064194443517"><a name="p1064194443517"></a><a name="p1064194443517"></a>您可以设置Topic的分区数，分区数越大消费的并发度越大。</p>
    <p id="p515812152115"><a name="p515812152115"></a><a name="p515812152115"></a>该参数设置为1时，消费消息时会按照先入先出的顺序进行消费。</p>
    <p id="p14572074216"><a name="p14572074216"></a><a name="p14572074216"></a>取值范围：1-20</p>
    <p id="p49191315152018"><a name="p49191315152018"></a><a name="p49191315152018"></a>默认值：3</p>
    </td>
    </tr>
    <tr id="row764164413519"><td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.3.1.1 "><p id="p2647442357"><a name="p2647442357"></a><a name="p2647442357"></a>副本数</p>
    </td>
    <td class="cellrowborder" valign="top" width="77%" headers="mcps1.2.3.1.2 "><p id="p133039601910"><a name="p133039601910"></a><a name="p133039601910"></a>您可以为每个Topic设置副本的数量，Kafka会自动在每个副本上备份数据，当其中一个Broker节点故障时数据依然是可用的，副本数越大可靠性越高。</p>
    <p id="p155911384258"><a name="p155911384258"></a><a name="p155911384258"></a>该参数设置为1时，表示只有一份数据。</p>
    <p id="p1420827152712"><a name="p1420827152712"></a><a name="p1420827152712"></a>取值范围：1-3</p>
    <p id="p74201827182717"><a name="p74201827182717"></a><a name="p74201827182717"></a>默认值：3</p>
    </td>
    </tr>
    <tr id="row464194417358"><td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.3.1.1 "><p id="p136464453511"><a name="p136464453511"></a><a name="p136464453511"></a>老化时间（小时）</p>
    </td>
    <td class="cellrowborder" valign="top" width="77%" headers="mcps1.2.3.1.2 "><p id="p166412448357"><a name="p166412448357"></a><a name="p166412448357"></a>Topic中的消息超过老化时间后，消息将会被删除，老化的消息无法被消费。</p>
    <p id="p1367151412910"><a name="p1367151412910"></a><a name="p1367151412910"></a>取值范围：1-168</p>
    <p id="p885211915294"><a name="p885211915294"></a><a name="p885211915294"></a>默认值：72</p>
    </td>
    </tr>
    <tr id="row24651137132"><td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.3.1.1 "><p id="p646518311134"><a name="p646518311134"></a><a name="p646518311134"></a>同步复制</p>
    </td>
    <td class="cellrowborder" valign="top" width="77%" headers="mcps1.2.3.1.2 "><p id="p74650321310"><a name="p74650321310"></a><a name="p74650321310"></a>开启同步复制后，需要在客户端配置acks=-1，否则无效。</p>
    </td>
    </tr>
    <tr id="row564184403515"><td class="cellrowborder" valign="top" width="23%" headers="mcps1.2.3.1.1 "><p id="p9641944123515"><a name="p9641944123515"></a><a name="p9641944123515"></a>同步落盘</p>
    </td>
    <td class="cellrowborder" valign="top" width="77%" headers="mcps1.2.3.1.2 "><p id="p1164144413516"><a name="p1164144413516"></a><a name="p1164144413516"></a>同步落盘是指生产的每条消息都会立即写入磁盘。</p>
    <p id="p121511193711"><a name="p121511193711"></a><a name="p121511193711"></a>开启：生产的每条消息都会立即写入磁盘，可靠性更高。</p>
    <p id="p0289112616719"><a name="p0289112616719"></a><a name="p0289112616719"></a>关闭：生产的消息存在内存中，不会立即写入磁盘。</p>
    </td>
    </tr>
    </tbody>
    </table>

8.  配置完成后，单击“确定”，完成创建Topic。


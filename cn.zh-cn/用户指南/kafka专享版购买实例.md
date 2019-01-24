# 购买实例<a name="dms-ug-180604013"></a>

## 操作场景<a name="section66578044"></a>

目前，DMS提供Kafka专享版实例的服务，Kafka专享版实例采用物理隔离的方式部署，租户独占Kafka实例。支持用户自定义规格和自定义特性，您可以根据业务需要定制相应计算能力和存储空间的Kafka实例。

## 前提条件<a name="section62331491"></a>

Kafka专享版实例运行于虚拟私有云，购买实例前，需保证有可用的虚拟私有云，并且已配置好安全组与子网。

创建虚拟私有云、安全组以及子网的方法，请参见《虚拟私有云用户指南》。

## 操作步骤<a name="section1474721314405"></a>

1.  登录管理控制台。
2.  在管理控制台左上角单击![](figures/icon-region.png)，选择区域。

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >此处请选择与租户的应用服务相同的区域。  

3.  单击页面上方的“服务列表”，选择“应用服务 \> 分布式消息服务”，进入分布式消息服务信息页面。
4.  单击左侧菜单栏的“Kafka专享版”，进入“Kafka专享版”页面。
5.  单击页面右上方的“购买实例”。

    每个项目默认最多可以创建100个Kafka专享版实例，如果您想创建更多队列，请联系客服申请增加配额。

6.  填写实例参数，参数说明如[表1](#table5373863818728)所示。

    **表 1**  参数说明

    <a name="table5373863818728"></a>
    <table><thead align="left"><tr id="row5933206518728"><th class="cellrowborder" valign="top" width="17%" id="mcps1.2.3.1.1"><p id="p5858956018728"><a name="p5858956018728"></a><a name="p5858956018728"></a>参数</p>
    </th>
    <th class="cellrowborder" valign="top" width="83%" id="mcps1.2.3.1.2"><p id="p4813390218728"><a name="p4813390218728"></a><a name="p4813390218728"></a>说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row4550153815252"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p135501238182512"><a name="p135501238182512"></a><a name="p135501238182512"></a>付费方式</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p19550438172515"><a name="p19550438172515"></a><a name="p19550438172515"></a>选择付费方式。</p>
    </td>
    </tr>
    <tr id="row153681361123"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p53681836827"><a name="p53681836827"></a><a name="p53681836827"></a>当前区域</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p183684366219"><a name="p183684366219"></a><a name="p183684366219"></a>DMS服务所在区域，可在页面左上角切换区域。</p>
    </td>
    </tr>
    <tr id="row113682295213"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p4866108918728"><a name="p4866108918728"></a><a name="p4866108918728"></a>可用区</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p4923409718728"><a name="p4923409718728"></a><a name="p4923409718728"></a>选择可用分区。</p>
    </td>
    </tr>
    <tr id="row5850290918728"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p4116798118728"><a name="p4116798118728"></a><a name="p4116798118728"></a>实例名称</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p3494740012058"><a name="p3494740012058"></a><a name="p3494740012058"></a>实例的名称，长度为4~64个字符。</p>
    <a name="ul665662631212"></a><a name="ul665662631212"></a><ul id="ul665662631212"><li>名称不能为空。</li><li>只能以英文字母开头。</li><li>长度为4到64位的字符串。</li><li>仅包含英文字母、数字、下划线（_）和中划线（-）。</li></ul>
    </td>
    </tr>
    <tr id="row16913610103113"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p788932455217"><a name="p788932455217"></a><a name="p788932455217"></a>描述（可选）</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p5890152419528"><a name="p5890152419528"></a><a name="p5890152419528"></a>实例描述的长度不超过1024。</p>
    </td>
    </tr>
    <tr id="row106831836183313"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p968383610333"><a name="p968383610333"></a><a name="p968383610333"></a>版本</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p36831936113320"><a name="p36831936113320"></a><a name="p36831936113320"></a>选择Kafka的版本号。</p>
    <p id="p13141195012199"><a name="p13141195012199"></a><a name="p13141195012199"></a>以“_plus”为后缀的版本由华为云DMS在开源Kafka的基础上做了增强。</p>
    </td>
    </tr>
    <tr id="row989313589517"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p1489375815114"><a name="p1489375815114"></a><a name="p1489375815114"></a>基准带宽</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p208933589516"><a name="p208933589516"></a><a name="p208933589516"></a>VPC内访问实例时，能稳定达到的带宽，单位为Byte/秒，支持100MB、300MB、600MB、1200MB。</p>
    <p id="p5756219192213"><a name="p5756219192213"></a><a name="p5756219192213"></a>为了保证业务的稳定性，当链接或者分区topic较多时，建议优先选择较大的带宽。</p>
    </td>
    </tr>
    <tr id="row8274161810208"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p62741918152017"><a name="p62741918152017"></a><a name="p62741918152017"></a>分区上限</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p727521802014"><a name="p727521802014"></a><a name="p727521802014"></a>指Kafka专享版实例可创建的最大分区总数。当所有topic的总分区数大于此值时创建topic失败。</p>
    <a name="ul195061648283"></a><a name="ul195061648283"></a><ul id="ul195061648283"><li>基准带宽为100MB时，分区上限为300。</li><li>基准带宽为300MB时，分区上限为900。</li><li>基准带宽为600MB时，分区上限为1800。</li><li>基准带宽为1200MB时，分区上限为1800。</li></ul>
    </td>
    </tr>
    <tr id="row093318317346"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p193323163413"><a name="p193323163413"></a><a name="p193323163413"></a>存储空间</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p771584611133"><a name="p771584611133"></a><a name="p771584611133"></a>存储Kafka数据的总磁盘大小。如果磁盘可用空间小于5%，将只能消费消息，不能生产消息。消息在老化后不再占用磁盘空间。</p>
    <p id="p5691439103819"><a name="p5691439103819"></a><a name="p5691439103819"></a>创建实例时会进行磁盘格式化，磁盘格式化会导致实际可用磁盘为总磁盘的93%~95%。</p>
    <a name="ul13437298449"></a><a name="ul13437298449"></a><ul id="ul13437298449"><li>基准带宽为100MB时，存储空间取值范围：600~90000。</li><li>基准带宽为300MB时，存储空间取值范围：1200~90000。</li><li>基准带宽为600MB时，存储空间取值范围：2400~90000。</li><li>基准带宽为1200MB时，存储空间取值范围：4800~90000。</li></ul>
    <div class="note" id="note7710122904515"><a name="note7710122904515"></a><a name="note7710122904515"></a><span class="notetitle"> 说明： </span><div class="notebody"><a name="ul4775730144610"></a><a name="ul4775730144610"></a><ul id="ul4775730144610"><li>高IO + 100MB带宽：假设平均消息体大小为1KB，则高吞吐场景可达10万条/秒，同步复制场景可达6万条/秒。</li><li>高IO + 300MB带宽 :  假设平均每条消息1KB，则高吞吐场景下可达30万条/秒，同步复制场景可达15万条/秒。</li><li>超高IO + 100MB带宽：假设平均消息体大小为1KB，则高吞吐场景可达10万条/秒，同步复制场景可达8万条/秒。</li><li>超高IO + 300MB带宽：假设平均每条消息1KB，则高吞吐场景可达30万条/秒，同步复制场景可达20万条/秒。</li><li>超高IO + 600MB带宽：假设平均每条消息1KB，则高吞吐场景可达60万条/秒，同步复制场景可达30万条/秒。</li><li>超高IO + 1200MB带宽：假设平均每条消息1KB，则高吞吐场景可达120万条/秒，同步复制场景可达40万条/秒。</li></ul>
    </div></div>
    </td>
    </tr>
    <tr id="row9846547161913"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p1384854771912"><a name="p1384854771912"></a><a name="p1384854771912"></a>转储</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p108061438152114"><a name="p108061438152114"></a><a name="p108061438152114"></a>开启或关闭转储。</p>
    <p id="p1848154791918"><a name="p1848154791918"></a><a name="p1848154791918"></a>通过开启转储将数据转储至OBS桶，实现数据的备份。</p>
    <div class="note" id="note16224183392310"><a name="note16224183392310"></a><a name="note16224183392310"></a><span class="notetitle"> 说明： </span><div class="notebody"><a name="ul1644912984811"></a><a name="ul1644912984811"></a><ul id="ul1644912984811"><li>消息包含消息属性（由属性名及属性值组成，以K-V的形式体现）时，属性名key不支持转储，属性值value支持转储。</li><li>当前开启转储后，暂不支持关闭转储。</li></ul>
    </div></div>
    </td>
    </tr>
    <tr id="row3119715618728"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p5533269218728"><a name="p5533269218728"></a><a name="p5533269218728"></a>虚拟私有云</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p5276310218728"><a name="p5276310218728"></a><a name="p5276310218728"></a>已创建的虚拟私有云。</p>
    <a name="ul353316111561"></a><a name="ul353316111561"></a><ul id="ul353316111561"><li>虚拟私有云可以为您的Kafka专享版实例构建隔离的、用户自主配置和管理的虚拟网络环境。</li><li>单击“查看虚拟私有云”，系统跳转到虚拟私有云界面，选择相应的虚拟私有云，可以查看安全组的出方向规则和入方向规则。</li></ul>
    </td>
    </tr>
    <tr id="row4851808618728"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p184411618728"><a name="p184411618728"></a><a name="p184411618728"></a>子网</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p1515573018728"><a name="p1515573018728"></a><a name="p1515573018728"></a>子网名称与IP地址段。</p>
    </td>
    </tr>
    <tr id="row196181012465"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p49541115154613"><a name="p49541115154613"></a><a name="p49541115154613"></a>安全组</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p395471584614"><a name="p395471584614"></a><a name="p395471584614"></a>已创建的安全组。</p>
    <p id="p35999277569"><a name="p35999277569"></a><a name="p35999277569"></a>安全组是一组对弹性云服务器的访问规则的集合，为同一个VPC内具有相同安全保护需求并相互信任的弹性云服务器提供访问策略。</p>
    </td>
    </tr>
    <tr id="row597018101248"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p1021123020242"><a name="p1021123020242"></a><a name="p1021123020242"></a>SSL</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p19919154792416"><a name="p19919154792416"></a><a name="p19919154792416"></a>客户端链接实例时SSL认证的开关。</p>
    <p id="p1092024722415"><a name="p1092024722415"></a><a name="p1092024722415"></a>开启SSL，则数据加密传输，安全性更高。</p>
    </td>
    </tr>
    <tr id="row44819143245"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p7637135516373"><a name="p7637135516373"></a><a name="p7637135516373"></a>用户名</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p1176515259472"><a name="p1176515259472"></a><a name="p1176515259472"></a>仅开启SSL认证才有该参数。</p>
    <p id="p12637195543714"><a name="p12637195543714"></a><a name="p12637195543714"></a>连接Kafka专享实例的用户名。</p>
    </td>
    </tr>
    <tr id="row19970131002418"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p3400959418728"><a name="p3400959418728"></a><a name="p3400959418728"></a>密码</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p92512634819"><a name="p92512634819"></a><a name="p92512634819"></a>仅开启SSL认证才有该参数。</p>
    <p id="p204469959544"><a name="p204469959544"></a><a name="p204469959544"></a>连接Kafka专享实例的密码。包括密码及确认密码。</p>
    <p id="p1205499104250"><a name="p1205499104250"></a><a name="p1205499104250"></a>Kafka专享实例密码复杂度要求：</p>
    <a name="ul65262816102030"></a><a name="ul65262816102030"></a><ul id="ul65262816102030"><li>密码不能为空。</li><li>输入长度为8到32位的字符串。</li><li>必须包含如下四种字符中的两种组合：<a name="ul1443183119407"></a><a name="ul1443183119407"></a><ul id="ul1443183119407"><li>小写字母</li><li>大写字母</li><li>数字</li><li>特殊字符包括（`~!@#$%^&amp;*()-_=+\|[{}]:'",&lt;.&gt;/?）</li></ul>
    </li></ul>
    </td>
    </tr>
    <tr id="row175574015417"><td class="cellrowborder" valign="top" width="17%" headers="mcps1.2.3.1.1 "><p id="p185589055411"><a name="p185589055411"></a><a name="p185589055411"></a>时间窗</p>
    </td>
    <td class="cellrowborder" valign="top" width="83%" headers="mcps1.2.3.1.2 "><p id="p2558130125418"><a name="p2558130125418"></a><a name="p2558130125418"></a>运维操作时间。</p>
    <p id="p13571145282612"><a name="p13571145282612"></a><a name="p13571145282612"></a>在这个时间段内，运维人员可以对该实例的节点进行维护操作。维护期间，业务可以正常使用，可能会发生闪断。维护操作通常几个月一次。</p>
    <p id="p538867566"><a name="p538867566"></a><a name="p538867566"></a>用户可选择22:00-02:00、02:00-06:00、06:00-10:00、10:00-14:00、14:00-18:00和18:00-22:00，在选择的时间段内，服务运维可对实例节点进行维护操作。</p>
    </td>
    </tr>
    </tbody>
    </table>

7.  填写完上述信息后，单击页面右侧的“立即申请”，进入“订单确认”页面。
8.  确认实例信息无误后，单击“提交订单”。开始创建Kafka专享版实例。
9.  Kafka专享版实例创建成功后，用户可以左侧导航栏的“Kafka专享版”页面，查看并管理自己的Kafka专享版实例。
    1.  创建Kafka专享版实例大约需要10到20分钟。
    2.  Kafka专享版实例创建成功后，默认“状态”为“运行中”。
    3.  如果创建Kafka专享版实例失败，可参考[删除实例](kafka专享版删除实例.md)，删除创建失败的Kafka专享版实例，然后重新申请。如果重新申请仍然失败，请联系客服。



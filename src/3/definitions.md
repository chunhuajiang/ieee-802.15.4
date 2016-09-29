# 3. 定义、缩略语和简写
## 3.1 定义 
　　为了完成本标准，使用了以下的术语和定义。没有在下面定义的其它术语可以在 *The Authoritative Dictionary of IEEE Standards Terms* 第七版 [B3].4 中找到。

　　**关联** - association：用于建立一个设备在网络中的成员关系的服务。

　　**授权标签** - authentication tag：用于验证一条消息授权的消息。

　　**信标使能 PAN 网络** - beacon-enabled personal area network：在一个 PAN 网络中，所有的协调器将发送周期性的信标，比如，有信标命令 <0x0F。

　　**线性调频** - chirp：线性调频。

　　**竞争接入阶段** - contention access period ：信标帧出现之后的一段时间，在这段时间内，希望发送数据的设备通过使用时隙 CSMA/CA 机制竞争访问信道。

　　**协调器** - coordinator：有传递信息能力的完全功能设备，如果一个协调器是 PAN 网络的主要控制器，就被称为 PAN 协调
器。

　　**数据授权** - data authentication：接收消息的实体确认消息中信源的真实性，并且在传输过程中没有被修改的过程。

　　**数据可靠性** - data authenticity：确保信源。

　　**设备** - device：执行 IEEE 802.15.4 MAC 层和物理层接口连接到无线媒介的操作的任一实体。 可能是精简功能设备(RFD)或全功能设备(FFD)。

　　**加密** - encryption：把信息转换为一种新的表现形式，因此需要有特权的信息去复原最初的信息。

　　**帧** - frame：来自 MAC 子层实体的被一起实时传输的聚合的比特的格式。

　　**完全功能设备(FFD)** - full-function device：

　　**组密钥** - group key：只被一组设备知道的密钥。

　　**密钥** - key：可能用到的保密信息，例如：用于保护信息对不能访问这些特权信息的组织暴露，以及/或被他们没有觉察的修改。

　　**密钥建立** - key establishment：两个或多个成员组建立一个密钥的过程。

　　**密钥材料** -  keying material：密钥与关联安全信息的组合(如当前值)。

　　**密钥管理** -  key management：系统上的密钥关系的建立与维护的过程的集合。

　　**连接密钥** -  link key：只在两个设备之间共用的一个密钥。

　　**移动设备** - mobile device：使用过程中可以在网络中改变逻辑位置的设备。

　　**非信标使能 PAN 网络** -  nonbeacon-enabled personal area network：协调器不产生规则的信标帧的PAN，例如信标命令 = 0X0F。

　　**临时值** - nonce：一个不重复的值，比如一个递增计数器，一个足够长的随机字符串，或者一个时间戳。

　　**孤立设备** - orphaned device：已经与它所连接的协调器失去联系的设备。

　　**包** - packet：通过物理介质一起实时传输的格式化的聚合比特。

　　**负载数据** -  payload data：被传输的数据信息内容。

　　**PAN 协调器** - personal area network (PAN) coordinator：个域网中的主要控制器。 IEEE 802.15.4 网络只有一个PAN 协调器。

　　**纯文本** - plain text：译出密码信息的字符串。

　　**测距功能设备** - ranging-capable device：支持测距功能的设备。

　　**精简功能设备(RFD)** - reduced-function device ：不能作为一个协调器工作的设备。

　　**对称密钥** - symmetric key：共用在两个或多个组织之间的一组密钥，用于加密技术/解密技术或合法保护/完整性确认，视用途而定。

　　**事务** - transaction：两个对等的介质访问控制实体媒介的相关的、连续的帧交换，要求 MAC 命令与数据帧的成功传输。

||||
|-|-|-|
|ASCII|American Standard Code for Information Interchange|信息互转标准码
|BIOS|Basic Input/Output System|
|CPU|Center Processing Unit|中央处理单元
|RAM|Random Access Memory|随机存储器
|ROM|Read-Only Memory|只读内存
|LIFO|Last In First Out|后进先出


|Ｗｏｒｄ|||
|-|-|-|
|Algorithm|算法| ['ælgərɪð(ə)m]
|Abstract| |['æbstrækt]
|Access|接入|['ækses]
|Advance|提前| [əd'vɑːns]
|Assemble|集合，汇编| [ə'semb(ə)l]
|Bit|比特（二进位制信息单位）| [bɪt]
|Byte|字节；8位元组|[baɪt]
|Unicode|统一码(采用双字节对字符进行编码)|['juːnɪˌkəʊd] 
|Word|2字节|[wɜːd]
|Catch| 捕捉|  [kætʃ]
|Cache|缓存| [kæʃ]
|Context|n.上下文| ['kɒntekst]
|Coordinate|n.坐标|[kəʊ'ɔ:dɪneɪt]
|Disassemble|vt.反汇编| [dɪsə'semb(ə)l]
|Pixel|n.像素|['piksəl]
|Render|vt.渲染| ['rendə]
|Raster| n.光栅;扫描线|
|Registry|n.注册,登记|
|Label|vt.标注|['leɪb(ə)l]
|Expression|表达（式） | [ɪkˈspreʃn]
|Evaluation|评估，求值 | [ɪˌvæljuˈeɪʃn]
|Provider|供应者|[prə'vaɪdə]|
|Feature|特征| ['fiːtʃə]
|Request|请求|[rɪ'kwest]
|Vector| 矢量|['vektə]
|Permission|许可| [pə'mɪʃ(ə)n]
|Priority |优先级| [praɪ'ɒrɪtɪ]
|Optimization|优化|
|Tolerance|公差|
|Segmentation|段|
|Geometry|几何图形|
|Effect|效果|
|Blend|混合|[blend]
|Mode|模式|[məʊd]
|Scheme|方案| [skiːm]
|Conditional|有条件的|[kən'dɪʃ(ə)n(ə)l]
|Hash|散列|[hæʃ]
|Iterator|迭代器|
|Process|进程，过程| [prəˈses;(for n,)ˈprəʊses]
|Thread|线程，螺纹| [θred]
|Dart||[dɑːt]
|Measurement|度量,尺寸| ['meʒəm(ə)nt]
|Item|条款;逐条列出| ['aɪtəm]
|Mutant|n.突变体|['mjuːt(ə)nt]
|Linear|线性的|['lɪnɪə]
|Conductivity|传导率|[ˌkɒndʌk'tɪvəti]
|Wave| 波动|[weɪv]
|Implicit| 含蓄的|[ɪm'plɪsɪt]
|Mutable|可变的|	['mjuːtəbl] 
|Syntax|语法 |['sɪntæks]
|Complex|复杂的；合成的 |['kɒmpleks]
|Register|寄存器|['redʒɪstə]
|Interface|接口|['ɪntəfeɪs]
|Intellisense| 智能感知 | [sens]
|External| 外部| [ik'stə:nəl]
|Crash|
|Dump| | [dʌmp]
|Offset|偏移| ['ɒfset]
|Effective| 有效的| [ɪ'fektɪv]
|Segment|n.段，vt.分割|['segm(ə)nt]
|Increase|增加| [ɪn'kriːs]
|Parity |相同，对等	|['pærəti]
|Push| 推 | [pʊʃ]
|Pull|拉|[pʊl]
|Hex| 十六进制 |  [heks]
|Tile| 贴片| [taɪl]

# Assemble

|Registry|||
|-|-|-|
|AH&AL = AX| Accumulator|累加寄存器
|BH&BL=BX| Base| 基址寄存器
|CH&CL=CX|Count| 计数寄存器
|DH&DL=DX|Data|数据寄存器
|SP|Stack Pointer|堆栈指针寄存器
|BP|Base Pointer|基址指针寄存器
|SI|Source Index| 源变址寄存器
|DI|Destination Index |目标变址寄存器
|DS|Data Segment |数据段寄存器
|ES|Extra Segment|附加段寄存器
|SS|Stack Segment|堆栈段寄存器
|CS| Code Segment| 代码段寄存器，指令段地址 
|IP| Instruction Pointer| 指令指针寄存器


|Flag|||
|-|-|-|
|OF|Overflow Flag|溢出标志
|SF|Sign Flag|符号标志
|ZF|Zero Flag|零标志
|CF|Carry Flag|进位标志
|AF|Auxiliary Carry Flag| 辅助进位标志
|PF|Parity Flag|奇偶标志
|DF|Direction Flag|方向标志
|IF|Interrupt Flag|中断标志
|TF|Trap Flag|陷阱标志


|Command|||
|-|-|-|
|1|


|Debug|||
|-|-|-|
|R|Registry| 查看，改变寄存器的内容
|D| | 查看内存内容
|E| Edit| 改写内存内容
|U||将内存中的机器指令翻译成汇编指令
|T||执行一条机器指令
|A|Assemble|以汇编指令的格式在内存中写入一条机器指令


# why 
- bit:

    计算机中的最小存储单元
    存储内容总是0或1
    所有二进制状态的实体都可以使用1bit表示
    8bits组成1byte
    不能够单独寻址

- byte：

    1byte包含8bits
    可以存储所有ASCII所有字符（这是它包含8bits的初衷）
    十进制整数范围[-128,127]或[0, 255]
    最小的可寻址存储单元

----
- $2^{4*x}$ 
    - ${4*5}$ : 8086地址总线个数20
    - ${4*4}$ : 8086数据总线个数16
    - $2^{4*2}$ 两位16进制数一个字节(存储单元)




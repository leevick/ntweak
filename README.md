# ntweak - A debugger for custom network protocol bellow transport layer

## Requirements

1. Support random or customized traffic (tcp/udp) to a designated network address.
2. Support transmission at constant time interval with precision up to millisecond.
3. Support single packet transmission
4. Support statistics of retransmission & disordered-transmission
5. Support the following statistics
   * latency (min,max,avg,distribution)
   * average data rate of transmission
   * data loss rate
6. Support Windows/Linux

# ntweak - 适用于传输层以下自定义网络的调试助手 

## 功能需求

1. 支持向指定网络地址发送自定义或随机网络数据，支持TCP/UDP协议
2. 支持控制单个数据包发送时间间隔,时间精确到毫秒级
3. 支持发送单个数据包
4. 支持重传与乱序检测与统计
5. 支持传输质量统计功能
   * 传输时延(最大,最小,平均,分布)
   * 平均传输速率
   * 丢包率
6. 支持Windows和Linux系统
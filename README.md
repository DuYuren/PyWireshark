# PyWireshark
用于上传国科大的软件与系统安全的作业
使用说明               
本项目基于scapy完成，能够按照网卡通过BPF表达式完成抓包，并且能够判断BPF表达式的正确性
- 步骤1：首先选择网卡，不选择默认为抓取所有网卡的数据包
- 步骤2：使用BPF表达式进行过滤，不填写为不使用
- 步骤3：停止抓包后会显示包列表，点击即可查看详细信息
- 步骤4：如果对于某个包TCP流感兴趣可以点击流追踪，即可完成IP+Port的流追踪功能。
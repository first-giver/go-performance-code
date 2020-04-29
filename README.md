# go-performance-code
This is Chen Yixiao's ppt at the 2020 gopher meet up in shenzhen.

## Go性能优化之路
**作者：陈一枭**

说明：这是腾讯高级工程师陈一枭在2020年初于深圳gopher meet up为大家演讲的PPT，内容非常干！PPT为操作指南，zip压缩包则是示例demo，每一步都有！

目录：
1. 何时性能优化
2. 如何性能优化
3. 性能优化实践

### 1.何时性能优化
- 何时开始
- 何时停止
### 2.如何性能优化
- 基准---benchmark的使用
- 分析工具：GODEBUG
- 分析工具：go tool pprof
- 分析工具：go tool trace
- 优化
- 校验
### 3.性能优化实践
- 示例使用sync.pool复用对象
- 使用成员变量复用对象
- 写时复制代替互斥锁
- 分区：减少共享数据结构争用
- 避免包含指针结构体作为map的key
- 使用string.Builder拼接字符串
- 其他

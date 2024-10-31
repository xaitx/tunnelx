## 目录结构信息
```
tunnel-proxy/
├── cmd/                     # 主程序
│   └── main.go              # 程序入口
├── connection/              # 连接管理器
│   └── manager.go           # 连接管理逻辑
├── protocol/                # 协议实现
│   ├── protocol.go          # 协议接口
│   ├── tcp.go               # TCP 协议实现
│   ├── udp.go               # UDP 协议实现
│   ├── icmp.go              # ICMP 协议实现
│   └── http.go              # HTTP 协议实现
├── processor/               # 数据处理器
│   └── processor.go         # 数据处理逻辑
├── plugins/                 # 插件目录，供第三方扩展
│   ├── example_plugin.go    # 示例插件
│   └── README.md            # 插件开发说明
└── README.md                # 项目说明
```
# infra-presets

🚀 **Infrastructure as Code (IaC) starts here.** 这是一个精心维护的基础设施配置预设仓库，旨在为 Nginx、Docker、Redis 等常用服务提供“即插即用”且符合最佳实践的配置文件模板。

## 🌟 特性
- **模块化设计**：配置高度解耦，易于组合。
- **生产就绪**：包含安全加固（SSL/HSTS）与性能优化（Gzip/Brotli）。
- **环境无关**：使用占位符，支持快速通过环境变量替换。

## 🛠 使用方法
1. 克隆仓库：`git clone https://github.com/yourname/infra-presets.git`
2. 进入对应目录，根据 `example.conf` 修改你的业务参数。
3. 生产环境建议通过 `include` 指令引用本仓库的配置片段。

## ⚠️ 注意
请勿在本仓库提交任何包含真实密码、密钥或证书的文件。建议使用 `.env` 或 Secret 管理工具。

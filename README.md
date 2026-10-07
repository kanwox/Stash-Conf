# Stash 规则分流配置

专为 iOS / macOS / tvOS 端 Stash 打造的精细化规则分流与 DNS 优化配置方案。

---

### 🚀 配置一键导入直达链接

在 Stash 中选择 **从 URL 下载** 并填入下方直达链接：

```text
https://raw.githubusercontent.com/kanwox/Stash-Conf/main/Stash_conf.yaml
```

---

## ⚡️ 核心特性一览

### 1. 独立服务分流
针对主流日常平台预设独立策略组，支持单独指定线路或交由主代理调度：
- **AI 智能服务**：ChatGPT、Claude 等海外 AI 独立调度
- **流媒体合集 (TV)**：整合 Netflix、Disney+、Prime Video、Apple TV+、HBO 统一管理
- **社媒与影音**：YouTube、X (Twitter)、TikTok、Twitch、Spotify、Telegram
- **开发与系统服务**：GitHub、Google、Apple、Microsoft
- **隐私拦截**：内置广告与追踪域名自动 REJECT 拦截

### 2. 地区自动优选
- 预置 **香港 (HK)、日本 (JP)、新加坡 (SG)、台湾 (TW)、美国 (US)** 5 大常用地区
- 采用 `url-test` 自动测速择优（默认隐藏后台运行，界面清爽不杂乱）
- 节点关键字正则过滤，自动剔除「流量、重置、到期、通知」等无效节点

### 3. 高性能规则集
- 采用 MetaCubeX **MRS 格式** 二进制规则集，加载极快、内存占用低
- 自动每周静默更新分流规则库，长期使用省心免维护

### 4. 纯净低延迟 DNS
- **Fake-IP 模式**，秒级解析出站
- 采用阿里 DNS (`dns.alidns.com`) 与腾讯 DNS (`doh.pub`) DoH 安全加密解析
- 国内域名与 CDN 分流绑定国内解析器，保留 CDN 本地就近加速效果

---

## 🛠 快速上手

1. **复制链接**：复制上方的配置直达链接。
2. **下载配置**：打开 Stash -> 配置 -> 从 URL 下载。
3. **填入订阅**：在文本编辑器中将 `url: "你的真实订阅链接"` 改为自己的订阅地址并保存。
4. **启动连接**：选择适合的策略模式，开启代理即可畅享。

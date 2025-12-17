# 🌐 Free Proxy Pool

自动更新的免费代理池，**每小时更新**。

> 最后更新: `2025-12-18 01:01:41 CST`

中文 | **[English](README_EN.md)**

---

## 📊 当前统计

| 类型 | 数量 |
|------|------|
| 代理总数 | 6,030 |
| 高匿代理 | 3,668 |
| 实时验证可用 | 29 |
| V2Ray 节点 | 245 |

---

## 📁 文件说明

### 🔥 推荐使用 (已验证可用)

| 文件 | 格式 | 数量 | 说明 |
|------|------|------|------|
| [`realtime_verified.txt`](realtime_verified.txt) | `ip:port` | 29 | ⭐ **实时验证可用**的代理，数量少但质量高 |
| [`realtime_verified_url.txt`](realtime_verified_url.txt) | `http://ip:port` | 29 | 同上，完整 URL 格式，可直接填入软件 |
| [`realtime_verified.json`](realtime_verified.json) | JSON | 29 | 同上，包含响应时间等详细信息 |

### 📋 HTTP/HTTPS 代理

| 文件 | 格式 | 数量 | 说明 |
|------|------|------|------|
| [`http.txt`](http.txt) | `ip:port` | 4,812 | HTTP 代理列表 |
| [`http_url.txt`](http_url.txt) | `http://ip:port` | 4,812 | HTTP 代理，完整 URL 格式 |
| [`https.txt`](https.txt) | `ip:port` | 173 | HTTPS 代理列表 |
| [`https_url.txt`](https_url.txt) | `https://ip:port` | 173 | HTTPS 代理，完整 URL 格式 |

### 🧦 SOCKS 代理

| 文件 | 格式 | 数量 | 说明 |
|------|------|------|------|
| [`socks4.txt`](socks4.txt) | `ip:port` | 936 | SOCKS4 代理列表 |
| [`socks4_url.txt`](socks4_url.txt) | `socks4://ip:port` | 936 | SOCKS4 代理，完整 URL 格式 |
| [`socks5.txt`](socks5.txt) | `ip:port` | 515 | SOCKS5 代理列表 |
| [`socks5_url.txt`](socks5_url.txt) | `socks5://ip:port` | 515 | SOCKS5 代理，完整 URL 格式 |

### 🎭 高匿代理 (Elite/High Anonymous)

| 文件 | 格式 | 数量 | 说明 |
|------|------|------|------|
| [`elite.txt`](elite.txt) | `ip:port` | 3,668 | 高匿代理，不暴露你的真实 IP |
| [`elite.json`](elite.json) | JSON | 3,668 | 高匿代理详细信息 (含国家、速度等) |
| [`elite_http_url.txt`](elite_http_url.txt) | `http://ip:port` | 3,535 | 高匿 HTTP 代理 |
| [`elite_socks5_url.txt`](elite_socks5_url.txt) | `socks5://ip:port` | 175 | 高匿 SOCKS5 代理 |

### 🚀 V2Ray / Clash 节点

| 文件 | 格式 | 数量 | 说明 |
|------|------|------|------|
| [`v2ray.txt`](v2ray.txt) | 原始链接 | 245 | V2Ray/Trojan/SS 节点，每行一个 |
| [`v2ray_subscribe.txt`](v2ray_subscribe.txt) | Base64 | 245 | V2Ray 订阅链接，直接导入客户端 |
| [`clash.yaml`](clash.yaml) | YAML | 50 | Clash 配置文件，可直接使用 |

### 📦 完整数据

| 文件 | 格式 | 数量 | 说明 |
|------|------|------|------|
| [`all.txt`](all.txt) | `ip:port` | 6,030 | 所有代理 (未验证) |
| [`all.json`](all.json) | JSON | 6,030 | 所有代理详细信息 |
| [`stats.json`](stats.json) | JSON | - | 统计信息 |

### 🔄 实时爬取 (未验证)

| 文件 | 格式 | 数量 | 说明 |
|------|------|------|------|
| [`realtime_all.txt`](realtime_all.txt) | `ip:port` | 300 | 实时爬取的所有代理 |
| [`realtime_all_url.txt`](realtime_all_url.txt) | `http://ip:port` | 300 | 同上，完整 URL 格式 |

---

## 💡 使用建议

1. **质量优先**: 使用 `realtime_verified*.txt`，这些是经过验证的可用代理
2. **数量优先**: 使用 `all.txt` 或按协议分类的文件
3. **高匿需求**: 使用 `elite*.txt`，这些代理不会暴露你的真实 IP
4. **科学上网**: 使用 `v2ray_subscribe.txt` 导入 V2Ray 客户端，或用 `clash.yaml`

---

## 🔗 Raw 链接

```
# 实时验证可用代理 (推荐)
https://raw.githubusercontent.com/YanStar/free-proxy/main/realtime_verified_url.txt

# HTTP 代理
https://raw.githubusercontent.com/YanStar/free-proxy/main/http_url.txt

# SOCKS5 代理
https://raw.githubusercontent.com/YanStar/free-proxy/main/socks5_url.txt

# V2Ray 订阅
https://raw.githubusercontent.com/YanStar/free-proxy/main/v2ray_subscribe.txt

# Clash 配置
https://raw.githubusercontent.com/YanStar/free-proxy/main/clash.yaml
```

---

## ⚠️ 免责声明

- 本项目仅供学习和研究使用
- 代理来源于公开网络，不保证可用性和安全性
- 请遵守当地法律法规，合理使用

---

⏰ 每小时自动更新 | 🤖 Powered by Docker

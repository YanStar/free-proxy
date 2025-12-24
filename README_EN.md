# 🌐 Free Proxy Pool

Auto-updated free proxy pool, **updated every hour**.

> Last Updated: `2025-12-24 14:01:32 CST`

**[中文文档](README.md)** | English

---

## 📊 Current Statistics

| Type | Count |
|------|-------|
| Total Proxies | 5,107 |
| Elite Proxies | 2,271 |
| Realtime Verified | 64 |
| V2Ray Nodes | 290 |

---

## 📁 File Description

### 🔥 Recommended (Verified & Working)

| File | Format | Count | Description |
|------|--------|-------|-------------|
| [`realtime_verified.txt`](realtime_verified.txt) | `ip:port` | 64 | ⭐ **Realtime verified** working proxies, fewer but high quality |
| [`realtime_verified_url.txt`](realtime_verified_url.txt) | `http://ip:port` | 64 | Same as above, full URL format, can be directly used in software |
| [`realtime_verified.json`](realtime_verified.json) | JSON | 64 | Same as above, includes response time and other details |

### 📋 HTTP/HTTPS Proxies

| File | Format | Count | Description |
|------|--------|-------|-------------|
| [`http.txt`](http.txt) | `ip:port` | 3,918 | HTTP proxy list |
| [`http_url.txt`](http_url.txt) | `http://ip:port` | 3,918 | HTTP proxies, full URL format |
| [`https.txt`](https.txt) | `ip:port` | 186 | HTTPS proxy list |
| [`https_url.txt`](https_url.txt) | `https://ip:port` | 186 | HTTPS proxies, full URL format |

### 🧦 SOCKS Proxies

| File | Format | Count | Description |
|------|--------|-------|-------------|
| [`socks4.txt`](socks4.txt) | `ip:port` | 986 | SOCKS4 proxy list |
| [`socks4_url.txt`](socks4_url.txt) | `socks4://ip:port` | 986 | SOCKS4 proxies, full URL format |
| [`socks5.txt`](socks5.txt) | `ip:port` | 497 | SOCKS5 proxy list |
| [`socks5_url.txt`](socks5_url.txt) | `socks5://ip:port` | 497 | SOCKS5 proxies, full URL format |

### 🎭 Elite Proxies (High Anonymous)

| File | Format | Count | Description |
|------|--------|-------|-------------|
| [`elite.txt`](elite.txt) | `ip:port` | 2,271 | Elite proxies, won't expose your real IP |
| [`elite.json`](elite.json) | JSON | 2,271 | Elite proxies with details (country, speed, etc.) |
| [`elite_http_url.txt`](elite_http_url.txt) | `http://ip:port` | 2,158 | Elite HTTP proxies |
| [`elite_socks5_url.txt`](elite_socks5_url.txt) | `socks5://ip:port` | 175 | Elite SOCKS5 proxies |

### 🚀 V2Ray / Clash Nodes

| File | Format | Count | Description |
|------|--------|-------|-------------|
| [`v2ray.txt`](v2ray.txt) | Raw links | 290 | V2Ray/Trojan/SS nodes, one per line |
| [`v2ray_subscribe.txt`](v2ray_subscribe.txt) | Base64 | 290 | V2Ray subscription, import directly to client |
| [`clash.yaml`](clash.yaml) | YAML | 50 | Clash config file, ready to use |

### 📦 Full Data

| File | Format | Count | Description |
|------|--------|-------|-------------|
| [`all.txt`](all.txt) | `ip:port` | 5,107 | All proxies (unverified) |
| [`all.json`](all.json) | JSON | 5,107 | All proxies with full details |
| [`stats.json`](stats.json) | JSON | - | Statistics |

### 🔄 Realtime Crawled (Unverified)

| File | Format | Count | Description |
|------|--------|-------|-------------|
| [`realtime_all.txt`](realtime_all.txt) | `ip:port` | 300 | All realtime crawled proxies |
| [`realtime_all_url.txt`](realtime_all_url.txt) | `http://ip:port` | 300 | Same as above, full URL format |

---

## 💡 Usage Tips

1. **Quality First**: Use `realtime_verified*.txt`, these are verified working proxies
2. **Quantity First**: Use `all.txt` or protocol-specific files
3. **Privacy Needs**: Use `elite*.txt`, these proxies won't expose your real IP
4. **Bypass Firewall**: Use `v2ray_subscribe.txt` to import into V2Ray client, or use `clash.yaml`

---

## 🔗 Raw Links

```
# Realtime verified proxies (Recommended)
https://raw.githubusercontent.com/YanStar/free-proxy/main/realtime_verified_url.txt

# HTTP proxies
https://raw.githubusercontent.com/YanStar/free-proxy/main/http_url.txt

# SOCKS5 proxies
https://raw.githubusercontent.com/YanStar/free-proxy/main/socks5_url.txt

# V2Ray subscription
https://raw.githubusercontent.com/YanStar/free-proxy/main/v2ray_subscribe.txt

# Clash config
https://raw.githubusercontent.com/YanStar/free-proxy/main/clash.yaml
```

---

## ⚠️ Disclaimer

- This project is for learning and research purposes only
- Proxies are collected from public sources, availability and security are not guaranteed
- Please comply with local laws and use responsibly

---

⏰ Auto-updated every hour | 🤖 Powered by Docker

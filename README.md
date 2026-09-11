# 🛡️ Anti-HttpSpy v5.3

Roblox Anti HttpSpy 检测脚本，保护你的 load http 不被泄露。

## ✨ 功能

- 🔍 检测 HttpSpy 等工具
- 🪝 Hook `game.HttpGet` / `game.HttpPost` 拦截敏感请求
- 🖥️ GUI 扫描（CoreGui / HUI）
- 🔬 GC 常量指纹扫描
- 💓 心跳持续监控
- 📡 Discord Webhook 告警（玩家信息、坐标、注入器等）
- 🥅 检测后自动 Kick 玩家

## 📦 使用
WEBHOOK_URL = "WebHOOK URL";
loadstring(game:HttpGet("https://你的托管地址/anti_httpspy.lua"))()

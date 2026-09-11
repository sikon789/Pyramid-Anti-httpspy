# Pyramid-Anti-httpspy

Roblox 外部加载脚本保护工具，防止 HttpSpy 等工具拦截 HttpGet 请求提取你的脚本。

## 功能

- 检测 HttpSpy 及常见注入器
- Hook `game.HttpGet` / `game.HttpPost` 监控
- GUI 注入扫描（CoreGui / HUI）
- GC 常量指纹扫描
- 心跳持续监控
- Discord Webhook 告警（玩家信息 / 坐标 / 注入器名称）
- 检测到后自动 Kick

## 使用

```lua
WEBHOOK_URL = "your_webhook_url_here"
loadstring(game:HttpGet("https://raw.githubusercontent.com/sikon789/Pyramid-Anti-httpspy/refs/heads/main/Pyramid%20Anti%20httpspy"))()
```

## 说明

- 纯客户端检测，配合脚本混淆效果更佳
- Webhook 建议走代理，不要直接暴露 Discord URL
- 检测到威胁后自动踢出玩家并上报

## 版本

v5.3

---

by 司空

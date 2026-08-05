# EMT·QQ

> 仿 Telegram 极简风格的 QQ 网页客户端 —— 聊天，本该如此优雅。

![demo](docs/38bfd84330491fccd43a0852bde1e753_720.jpg)

## ✨ 特性

- **🎨 仿 Telegram 极简设计** — 毛玻璃质感、圆角气泡、纯净配色，中心面板通透无遮挡，壁纸之美自然透出
- **⚡ 丝滑流畅** — 动态表情、贴纸、消息动画轻量优化，滚动跟手、切换零等待
- **😀 超 1000 款动态 Emoji** — 收录 1069 个 Telegram 同款 TGS 动态表情，全矢量动画：表情会动、会眨眼、会跳舞
- **🖼️ 海量动态贴纸** — 4 大系列动态贴纸：经典角色、小鸭子、死神笔记、小火人，发送即播放
- **🎨 个性定制** — 8 套主题配色 × 13 张精选壁纸 × 浅色 / 深色 / 夜间三重视觉模式，可调气泡颜色与圆度
- **🔧 进阶功能** — 阅后即撤、AI 润色、定时发送、表格投票、一键分离模式等

![demo](docs/f1a7f362667ffe6f4707a53d167a4876_720.jpg)

## 🚀 快速开始

```bash
# 1. 安装依赖
npm install

# 2. 启动服务
node server-proxy.cjs

# 3. 浏览器打开
http://127.0.0.1:8098/
```

> 需要配合 NapCat 使用（QQ 协议层），详见项目文档。

## 📁 项目结构

```
emt-qq-client/
├── server-proxy.cjs    # 本地代理服务（静态资源 + API 中转）
├── start.bat           # 一键启动脚本
├── dist2/              # 客户端
│   ├── qq-client.html  # 主客户端页面
│   ├── tgs/            # 动态 emoji 素材
│   ├── st_dn/ st_pm/   # 动态贴纸素材
│   ├── st_fl/ st_du/
│   └── bg*.webp/png    # 壁纸素材
└── README.md
```

## 🛠️ 技术栈

- HTML / CSS / JavaScript（原生，零框架）
- Lottie 动画渲染
- WebSocket 实时通信

## 📄 License

MIT

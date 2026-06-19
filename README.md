# ❤️ AI 女友 - 小雅

一个可以在浏览器里和你聊天的 AI 女友网站。真实风格照片 + 智能对话。

## 🚀 在线使用

打开网站后，首次使用需要配置 API Key：

1. 访问 [阿里云 DashScope](https://dashscope.console.aliyun.com)（支付宝扫码登录）
2. 开通 **灵积模型服务**
3. 获取 API Key（以 `sk-` 开头）
4. 粘贴到网站的设置弹窗中，保存即可

> 🔒 API Key 只存储在浏览器本地，不会上传到任何服务器

## 💰 费用

完全免费！通义千问每月赠送 **200 万 token**，足够日常聊天使用。

## 📸 照片

照片由 AI 生成，存放在 `images/` 目录下。你可以替换为自己的照片：
- 替换 `images/photo1.jpg` ~ `photo4.jpg`
- 修改 `index.html` 中 `photos` 数组的 `label` 文字
- 建议图片尺寸：720×960（竖版写真比例）

### 生成更多照片

推荐使用以下免费 AI 绘图工具生成真实风格人像：

| 平台 | 地址 | 特点 |
|------|------|------|
| SeaArt | seaart.ai | 免费额度，写实模型丰富 |
| TensorArt | tensor.art | 每日免费额度 |
| 通义万相 | tongyi.aliyun.com | 阿里出品，国内直连 |

**推荐提示词**：
> 真实摄影风格，中国美女，25岁，长发，时尚穿搭，高清写真，半身照，自然光线，背景虚化

## 🛠️ 本地运行

直接在浏览器打开 `index.html` 即可，无需任何服务器。

## 🌐 部署到 GitHub Pages

1. Fork 或克隆本仓库
2. 推送到你的 GitHub：
```bash
git add .
git commit -m "AI girlfriend website"
git push origin main
```
3. 在仓库 Settings → Pages 中，选择 `main` 分支，点击 Save
4. 等待几分钟，即可通过 `https://你的用户名.github.io/ai-girlfriend` 访问

## ⚙️ 技术栈

- 纯 HTML + CSS + JavaScript，零依赖
- AI 对话：通义千问 (Qwen-Plus) 免费 API
- 托管：GitHub Pages

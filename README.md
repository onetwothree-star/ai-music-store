# AI Music Store - 独立站

## 快速启动

### 本地预览
```bash
cd /tmp/ai-music-store
python3 -m http.server 8080
# 然后访问 http://localhost:8080
```

### 部署到免费托管

**选项 1: GitHub Pages (推荐)**
1. 创建 GitHub 仓库
2. 上传所有文件
3. Settings → Pages → 启用

**选项 2: Netlify**
1. netlify.com 注册
2. 拖拽上传文件夹
3. 自动生成网址

**选项 3: Vercel**
1. vercel.com 注册
2. Import Project
3. 上传文件

## 文件结构
```
ai-music-store/
├── index.html          # 主页面
├── samples/           # 音频样品 (需上传)
│   ├── happy_upbeat_preview.mp3
│   ├── relaxing_calm_preview.mp3
│   ├── energetic_cinematic_preview.mp3
│   └── summer_beach_preview.mp3
└── README.md
```

## 支付集成

### 方案 A: Gumroad (最简单)
1. gumroad.com 创建产品
2. 获取产品链接
3. 替换 buy-button 的链接

### 方案 B: Stripe
1. stripe.com 注册
2. 创建 Payment Link
3. 替换链接

### 方案 C: 手动联系
1. 展示 Telegram/微信
2. 人工确认付款
3. 人工发货

## 自定义修改

1. 修改 `index.html` 中的联系信息
2. 替换 samples/ 中的音频文件
3. 修改价格和套餐

## TODO
- [ ] 添加更多音乐样品
- [ ] 集成支付系统
- [ ] 添加在线试听完整版
- [ ] SEO 优化
- [ ] 添加 Google Analytics

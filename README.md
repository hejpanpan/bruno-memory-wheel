# 布鲁诺记忆轮 (Bruno Memory Wheel)

基于乔尔丹诺·布鲁诺《论观念的影子》（1582）的记忆术工具，采用任天堂像素风设计。

![像素风](https://img.shields.io/badge/style-NES%20Pixel-green)
![React](https://img.shields.io/badge/React-18-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)

## 功能

- **记忆之轮** — 三圈字母编码系统（人物/动作/道具），支持单轮3字母和双轮6字母模式
- **整段记忆** — 中英文智能分块，音节感知的文本切分
- **记忆宫殿** — 可自定义房间模板，支持像素编辑器绘制背景、拖拽标记
- **自定义标记** — 支持emoji/像素绘制/图片上传三种图标类型
- **练习模式** — 随机抽测编码记忆
- **对照表** — 完整26字母编码速查

## 在线体验

https://jhi7ll2drdpoo.ok.kimi.link

## 本地开发

```bash
# 安装依赖
npm install

# 开发服务器
npm run dev

# 构建
npm run build
```

## 技术栈

- React 18 + TypeScript + Vite
- Tailwind CSS
- 纯前端，localStorage 本地存储

## 配色风格

任天堂像素风（NES/SNES）：
- 背景：羊皮纸米色 `#e8e0d0`
- 外环：马里奥红 `#e4000f`
- 中环：路易吉绿 `#00a030`
- 内环：林克蓝 `#0077b6`
- 强调：金币黄 `#d4a017`

# 交互式唱片播放器

这是一个交互式的唱片播放器界面，具有动画效果和音频播放功能。

## 功能特性

- 点击专辑封面，对应的唱片会显示并平滑移动到播放器中心
- 播放对应专辑的音乐
- 平滑的动画过渡效果
- 悬停时专辑封面会放大

## 文件说明

### 需要的音频文件

请将以下三个 mp3 文件放置在项目根目录：

1. **After_Hours.mp3** - The Weeknd 的音乐
2. **Oh_Darling.mp3** - The Beatles 的音乐
3. **We_Don't_Talk_Anymore.mp3** - Charlie Puth 的音乐

### 项目文件

- `index.html` - 主页面文件
- `Recordplayer.svg` - 唱片播放器的 SVG 图形
- `After_Hours.mp3` - Weeknd 专辑音乐
- `Oh_Darling.mp3` - Beatles 专辑音乐
- `We_Don't_Talk_Anymore.mp3` - Charlie Puth 专辑音乐

## 使用方法

1. 确保所有 mp3 文件都在项目根目录下
2. 在浏览器中打开 `index.html`
3. 点击左侧的三个专辑封面之一：
   - **Weeknd** (顶部) - 播放 After Hours
   - **Beatles** (中部) - 播放 Oh! Darling
   - **Charlie** (底部) - 播放 We Don't Talk Anymore

## 技术特性

- 纯 HTML/CSS/JavaScript 实现
- SVG 内嵌样式和动画
- HTML5 Audio API
- CSS transitions 和 transforms
- 响应式设计

## 音频映射

| 专辑封面 | 唱片 | 音频文件 |
|---------|------|---------|
| Weeknd | WeekndRecord | After_Hours.mp3 |
| Beatles | BeatlesRecord | Oh_Darling.mp3 |
| Charlie | CharlieRecord | We_Don't_Talk_Anymore.mp3 |

## 交互行为

- 点击不同的专辑封面会切换唱片和音乐
- 切换时，当前播放的音乐会停止，新的音乐会开始播放
- 音乐会循环播放
- 唱片移动到播放器中心需要 0.8 秒
- 淡入效果需要 0.3 秒

## 注意事项

- 音频文件需要用户交互（点击）才能播放（浏览器安全策略）
- 确保音频文件路径正确
- 建议使用现代浏览器（Chrome, Firefox, Safari, Edge）

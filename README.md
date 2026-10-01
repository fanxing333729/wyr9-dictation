# wyr9-dictation

> 外研版九年级英语单词默写工具 —— 一个纯前端、开箱即用的在线单词听写与记忆辅助应用。

![HTML](https://img.shields.io/badge/HTML-100%25-orange)
![License](https://img.shields.io/badge/license-MIT-green)
![Deploy](https://img.shields.io/badge/deploy-GitHub%20Pages-blue)

## ✨ 功能特性

### 📚 教材覆盖
- **外研版九年级上册（9A）** 全单元单词
- **外研版九年级下册（9B）** 全单元单词
- 按单元 / 模块分类，按需选择默写范围

### 🎧 听写与默写
- **语音朗读**：内置 TTS 引擎，自动朗读单词，支持真人发音节奏
- **多种模式**：看中文写英文、听英文写中文、中英互译等
- **即时反馈**：提交后立即判分，标注正确 / 错误
- **屏幕常亮**：默写过程中自动保持屏幕唤醒，不中断

### 📊 学习数据
- **个人仪表盘**：正确率、练习次数、掌握进度一目了然
- **雷达图分析**：多维度能力评估（基于 Chart.js）
- **遗忘曲线**：根据艾宾浩斯遗忘曲线追踪记忆状态
- **智能评语**：根据成绩自动生成鼓励性评价

### 📝 错词与收藏
- **错词本**：自动收录拼写错误的单词，方便针对性复习
- **收藏夹**：手动标记重点 / 难点单词
- **错题重练**：一键从错词本生成专项练习

### 🏆 成就系统
- 多维度成就徽章，激励持续学习
- 解锁条件实时追踪

### ☁️ 云端同步
- 基于 Supabase 的云端数据同步
- 多设备共享学习进度、错词本与收藏
- 本地优先，离线可用，联网自动同步

### 🎨 界面与体验
- **深色 / 浅色模式**：跟随系统或手动切换
- **移动端优先**：响应式设计，手机 / 平板 / 电脑均可使用
- **键盘避让**：移动端输入时自动调整视图，避免遮挡
- **分享二维码**：成绩一键生成二维码分享

## 🚀 快速开始

### 在线使用（推荐）

项目已部署至 GitHub Pages，直接访问即可使用：

🔗 **https://fanxing333729.github.io/wyr9-dictation/**

### 本地运行

本项目为纯静态单页应用，无需构建工具：

```bash
# 克隆仓库
git clone https://github.com/fanxing333729/wyr9-dictation.git

# 进入目录
cd wyr9-dictation

# 直接用浏览器打开 index.html，或启动本地服务器
# 方式一：双击 index.html
# 方式二：Python 本地服务器
python -m http.server 8080
# 然后访问 http://localhost:8080
```

## 🛠 技术栈

| 类别 | 技术 |
|------|------|
| 结构 | HTML5（单文件应用） |
| 样式 | 原生 CSS，CSS 变量主题系统 |
| 交互 | 原生 JavaScript（ES6+） |
| 图表 | Chart.js（雷达图、遗忘曲线） |
| 语音 | Web Speech API（TTS） |
| 二维码 | qrcode.js |
| 云端 | Supabase（数据同步） |
| 部署 | GitHub Pages |

## 📁 项目结构

```
wyr9-dictation/
├── index.html      # 主应用（含全部 HTML / CSS / JS，单文件）
├── README.md       # 项目说明
└── .github/        # GitHub Pages 部署配置
```

> 项目采用单文件架构，所有样式与脚本均内联在 `index.html` 中，便于部署和分享。

## 📖 使用说明

1. **选择教材**：在首页选择九年级上册或下册
2. **选择单元**：勾选要默写的单元（可多选）
3. **开始默写**：点击开始，听发音或看中文提示，输入英文单词
4. **查看结果**：提交后查看得分、错题解析
5. **复习巩固**：在错词本中针对错误单词反复练习
6. **云端同步**：登录后自动同步学习数据到云端

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

## 📄 许可证

本项目采用 [MIT License](LICENSE) 开源协议。

---

⭐ 如果这个工具对你有帮助，欢迎点个 Star 支持一下！

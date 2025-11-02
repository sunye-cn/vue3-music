<div align="center">
  <h1>🎵 Vue3 Music</h1>
  <p>基于 Vue 3 的现代化音乐播放器应用</p>
  
  [![Vue](https://img.shields.io/badge/Vue-3.x-brightgreen.svg)](https://vuejs.org/)
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
  [![Node](https://img.shields.io/badge/node-%3E%3D14.x-success.svg)](https://nodejs.org/)
</div>

## ✨ 特性

- 🎨 现代化 UI 设计
- 🎵 完整的音乐播放功能
- 📱 响应式布局,支持移动端
- 🎯 Vue 3 Composition API
- 🔥 热模块替换(HMR)
- 📦 优化的构建配置

## 📸 预览

<!-- 建议添加项目截图 -->
> 💡 提示: 可以添加应用截图或 GIF 演示

## 🚀 快速开始

### 环境要求

- Node.js >= 14.x (推荐使用 16.x LTS)
- npm >= 6.x 或 yarn >= 1.22.x

### 安装依赖

```bash
npm install
# 或使用 yarn
# yarn install
```

### 开发环境

```bash
npm run serve
```

访问 `http://localhost:8080` 查看应用

### 生产构建

```bash
npm run build
```

构建文件将生成在 `dist` 目录

### Lints and fixes files

```bash
npm run lint
```

## 📦 技术栈

| 技术 | 版本 | 说明 |
|------|------|------|
| Vue | 3.x | 渐进式 JavaScript 框架 |
| Vuex | 4.x | 状态管理 |
| Vue Router | 4.x | 路由管理 |
| Sass | - | CSS 预处理器 |
| Webpack | 5.x | 模块打包工具 |
| ESLint | - | 代码检查工具 |

## 📁 项目结构

```
vue3-music/
├── public/              # 静态资源
├── src/
│   ├── assets/         # 资源文件(图片、样式等)
│   │   ├── images/     # 图片资源
│   │   └── scss/       # 全局样式
│   ├── components/     # 组件
│   │   ├── base/       # 基础组件
│   │   ├── player/     # 播放器组件
│   │   ├── music-list/ # 音乐列表组件
│   │   └── ...
│   ├── router/         # 路由配置
│   ├── store/          # 状态管理
│   │   ├── modules/    # Vuex 模块
│   │   └── index.js    # Store 入口
│   ├── views/          # 页面视图
│   ├── utils/          # 工具函数
│   ├── api/            # API 接口
│   ├── App.vue         # 根组件
│   └── main.js         # 入口文件
├── .eslintrc.js        # ESLint 配置
├── babel.config.js     # Babel 配置
├── vue.config.js       # Vue CLI 配置
├── package.json
└── README.md
```

## 🎯 核心功能

### 播放器功能
- ✅ 音乐播放/暂停
- ✅ 上一曲/下一曲
- ✅ 播放模式切换(顺序/随机/单曲循环)
- ✅ 进度条控制
- ✅ 音量控制

### 列表管理
- ✅ 播放列表管理
- ✅ 收藏/喜欢
- ✅ 历史记录

### 其他功能
- ✅ 歌词滚动显示
- ✅ 搜索功能
- ✅ 响应式设计

## 🔧 开发命令

```bash
# 安装依赖
npm install

# 启动开发服务器(热重载)
npm run serve

# 生产构建(压缩优化)
npm run build

# 代码检查
npm run lint

# 代码格式化
npm run lint -- --fix
```

## 📝 代码规范

项目使用 ESLint 进行代码规范检查,遵循以下规范:

- ✅ Vue 官方风格指南
- ✅ JavaScript Standard Style
- ✅ 提交前自动检查

## 🐛 常见问题

### 安装依赖失败?
```bash
# 清除缓存后重试
npm cache clean --force
rm -rf node_modules package-lock.json
npm install
```

### Sass 编译警告?
项目使用 `sass` 替代 `node-sass`,警告不影响正常使用

## 🤝 贡献指南

欢迎贡献代码! 请遵循以下步骤:

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 提交 Pull Request

## 📄 许可证

本项目采用 [MIT License](LICENSE) 开源协议

## 👨‍💻 作者

**sunye** - [@sunye-cn](https://github.com/sunye-cn)

## 🙏 致谢

- [Vue.js](https://vuejs.org/) - 渐进式 JavaScript 框架
- [Vue CLI](https://cli.vuejs.org/) - Vue.js 开发标准工具
- 感谢所有为本项目做出贡献的开发者

## 📮 联系方式

- GitHub: [@sunye-cn](https://github.com/sunye-cn)
- Issue: [提交问题](https://github.com/sunye-cn/vue3-music/issues)

---

<div align="center">
  ⭐️ 如果这个项目对你有帮助,请给个 Star! ⭐️
</div>

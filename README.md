# Keaton 的世界

这是我的个人学习成长网站，记录学习笔记、成长感悟、阅读心得和喜爱的事物。

## 🌟 网站特色

- **成长之路**：记录学习历程和成长感悟
- **领域学习**：AI、社会医学、社会科学、文学艺术
- **阅读记录**：分享读书心得和推荐
- **喜爱的事物**：电影、音乐、工具推荐

## 🚀 技术栈

- **静态网站生成器**：Hugo
- **主题**：PaperMod
- **部署**：GitHub Pages
- **自动化**：GitHub Actions

## 📝 本地开发

### 环境要求
- Hugo Extended 版本
- Git

### 运行步骤
1. 克隆仓库
```bash
git clone https://github.com/Lan-Keeting/New_World_Keaton.git
cd New_World_Keaton
```

2. 启动开发服务器
```bash
hugo server --bind 0.0.0.0 --port 1314
```

3. 访问网站
打开浏览器访问 `http://localhost:1314`

## 🌐 在线访问

网站地址：https://lan-keeting.github.io/Keaton_Websites/

## 📁 项目结构

```
New_World_Keaton/
├── content/          # 网站内容
│   ├── _index.md     # 首页
│   ├── about/        # 关于页面
│   └── guide/        # 成长之路
│       ├── learning/ # 领域学习
│       ├── reflection/ # 成长感悟
│       ├── reading/  # 阅读记录
│       └── favorites/ # 喜爱的事物
├── layouts/          # 自定义布局
├── static/           # 静态资源
├── themes/           # 主题文件
└── hugo.toml         # 配置文件
```

## 🔄 自动部署

网站使用GitHub Actions自动部署：
- 推送代码到main分支时自动构建
- 构建完成后自动部署到GitHub Pages
- 支持手动触发部署

## 📄 许可证

MIT License

## 🤝 联系方式

- GitHub: [@Lan-Keeting](https://github.com/Lan-Keeting)
- 网站: https://lan-keeting.github.io/Keaton_Websites/

---

*让我们一起在学习的道路上不断前行！*

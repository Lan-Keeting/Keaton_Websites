# 网站部署说明

## 🚀 部署到 GitHub Pages

### 步骤 1: 创建 GitHub 仓库
1. 在 GitHub 上创建一个新的仓库，命名为 `New_World_Keaton`
2. 确保仓库是公开的（public）

### 步骤 2: 使用 GitHub Desktop 上传
1. 打开 GitHub Desktop
2. 选择 "Add" → "Add existing repository"
3. 选择您的本地项目文件夹 `D:\Keaton_World\Keaton_Website`
4. 点击 "Add repository"

### 步骤 3: 首次提交
1. 在 GitHub Desktop 中，您会看到所有文件都被标记为 "new"
2. 在左下角添加提交信息：`Initial commit: Add Hugo website`
3. 点击 "Commit to main"

### 步骤 4: 推送到 GitHub
1. 点击 "Push origin" 将代码推送到 GitHub
2. 等待推送完成

### 步骤 5: 配置 GitHub Pages
1. 在 GitHub 仓库页面，点击 "Settings"
2. 在左侧菜单中找到 "Pages"
3. 在 "Source" 部分，选择 "GitHub Actions"
4. 保存设置

### 步骤 6: 等待自动部署
1. 推送代码后，GitHub Actions 会自动开始构建
2. 在仓库页面点击 "Actions" 标签查看构建进度
3. 构建完成后，网站将自动部署

## 🌐 访问网站

部署完成后，您的网站将可以通过以下地址访问：
**https://lan-keeting.github.io/New_World_Keaton/**

## 📝 后续更新

每次您想要更新网站时：
1. 在本地修改文件
2. 在 GitHub Desktop 中提交更改
3. 推送到 GitHub
4. GitHub Actions 会自动重新构建和部署

## 🔧 故障排除

### 如果构建失败
1. 检查 GitHub Actions 日志
2. 确保所有文件路径正确
3. 验证 Hugo 配置语法

### 如果网站无法访问
1. 确保仓库是公开的
2. 检查 GitHub Pages 设置
3. 等待几分钟让 DNS 传播

## 📞 支持

如果遇到问题，请检查：
- GitHub Actions 日志
- Hugo 构建日志
- 浏览器控制台错误

---

*祝您部署顺利！* 
# 部署指南：将个人博客部署到 GitHub Pages

## 步骤 1: 创建 GitHub 仓库

1. 登录 GitHub 账户
2. 点击 "New repository" 创建新仓库
3. 仓库名称设置为 `xuhongliang.github.io`
4. 设置为 Public（公开）
5. 选择 "Add a README file"（可选）
6. 点击 "Create repository"

## 步骤 2: 将文件上传到仓库

### 方法 1: 使用命令行 (Git)

```bash
# 克隆仓库到本地
git clone https://github.com/xuhongliang/xuhongliang.github.io.git
cd xuhongliang.github.io

# 将 index.html 文件复制到仓库目录
cp /path/to/your/index.html .

# 添加文件到 Git
git add .
git commit -m "Initial commit: Add personal blog homepage"
git push origin main
```

### 方法 2: 使用 GitHub 网页界面

1. 进入您的仓库页面
2. 点击 "Add file" → "Upload files"
3. 将 `index.html` 文件拖拽到上传区域
4. 点击 "Commit changes"

## 步骤 3: 启用 GitHub Pages

1. 进入仓库页面
2. 点击 "Settings" 标签
3. 向下滚动到 "Pages" 部分
4. 在 "Source" 下拉菜单中选择 "Deploy from a branch"
5. 选择 "main" 分支和 "/" 文件夹
6. 点击 "Save"
7. 等待页面刷新，您会看到类似 "Your site is published at https://xuhongliang.github.io/" 的消息

## 步骤 4: 访问您的网站

部署完成后，您可以通过以下地址访问您的个人博客：
https://xuhongliang.github.io/

注意：首次部署可能需要几分钟时间生效。

## 额外提示

1. 如果您想添加更多页面，只需将相应的 HTML 文件上传到仓库
2. 您也可以添加 CSS、JavaScript 和图片文件来增强网站
3. 确保所有文件都在仓库的根目录下，或在 `docs` 文件夹中（如果您在设置中选择了该选项）

## 故障排除

如果网站无法访问：
1. 检查仓库名称是否为 `xuhongliang.github.io`
2. 确认 GitHub Pages 已在仓库设置中启用
3. 确保至少有一个 HTML 文件在仓库中
4. 检查是否使用了正确的分支（通常是 main 或 master）
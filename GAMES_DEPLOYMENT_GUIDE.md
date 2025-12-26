# 部署指南：将个人博客和俄罗斯方块游戏部署到 GitHub Pages

## 文件清单
- index.html - 个人博客主页
- tetris.html - 俄罗斯方块游戏页面
- images/ - 图片资源目录
- stylesheets/ - 样式表目录
- javascripts/ - JavaScript文件目录

## 部署步骤

### 1. 创建 GitHub 仓库
1. 登录 GitHub，创建一个新的仓库
2. 仓库名称必须为 `yourusername.github.io`（例如：`xuhongliang.github.io`）
3. 选择公开（Public）选项
4. 不要初始化仓库（不添加 README、.gitignore 或 license）

### 2. 上传文件
1. 在仓库页面点击 "Add file" → "Upload files"
2. 将以下文件拖拽到上传区域：
   - index.html
   - tetris.html
   - images/ 目录
   - stylesheets/ 目录
   - javascripts/ 目录
3. 点击 "Commit changes" 提交文件

### 3. 启用 GitHub Pages
1. 在仓库页面点击 "Settings" 选项卡
2. 向下滚动到 "Pages" 部分
3. 在 "Source" 下拉菜单中选择 "Deploy from a branch"
4. 选择 "main" 分支并点击 "Save"
5. GitHub Pages 会自动部署，稍后会显示部署成功的消息

### 4. 访问网站
- 部署完成后，访问 `https://yourusername.github.io` 即可看到你的个人博客
- 俄罗斯方块游戏可通过 `https://yourusername.github.io/tetris.html` 访问

## 注意事项
- 确保所有文件都已上传到仓库
- GitHub Pages 部署可能需要几分钟时间
- 如果网站无法访问，请检查仓库名称是否正确
- 确保源设置为正确的分支（main）

## 自定义
- 要修改博客内容，编辑 index.html 文件
- 要调整俄罗斯方块游戏，编辑 tetris.html 文件
- 上传修改后的文件到 GitHub 仓库即可更新网站
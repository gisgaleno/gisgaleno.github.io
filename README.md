# GIS Galeno's Blog

基于 Jekyll Chirpy 主题的个人博客网站。

## 本地开发

### 环境要求
- Ruby 3.1+
- Node.js 18+
- Bundler
- Git

### 安装依赖
```bash
# 安装 Ruby 依赖
bundle install

# 安装 Node.js 依赖
npm install
```

### 本地运行
```bash
# 构建前端资源
npm run build

# 启动本地服务器
bundle exec jekyll serve --livereload
```

访问 `http://localhost:4000` 查看网站。

## 部署到 GitHub Pages

本项目已配置 GitHub Actions 自动部署：

1. 将代码推送到 `main` 分支
2. GitHub Actions 会自动构建并部署到 GitHub Pages
3. 网站将在 `https://gisgaleno.github.io` 上可用

### 手动部署步骤

1. 在 GitHub 仓库设置中启用 Pages
2. 选择 "GitHub Actions" 作为源
3. 推送代码到 `main` 分支
4. 等待 Actions 完成构建和部署

## 配置说明

主要配置文件：
- `_config.yml` - Jekyll 和主题配置
- `.github/workflows/pages-deploy.yml` - GitHub Actions 工作流

## 许可证

MIT License
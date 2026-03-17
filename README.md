# CogniBlock Community

一个现代化的知识分享社区平台，专为学习者和教育者打造。通过知识卡片和知识库的形式，让知识的创建、分享和获取变得更加高效和有趣。

## ✨ 特性

- **知识库浏览** - 系统化的学科知识内容，支持数学、物理、化学、生物等多个学科
- **知识卡片** - 快速记忆和复习的卡片式学习内容
- **智能搜索** - 支持全文搜索和分类筛选
- **响应式设计** - 完美适配桌面端和移动端
- **现代化UI** - 基于 Tailwind CSS 的美观界面
- **流畅动画** - 使用 GSAP 实现的页面转场动画
- **Markdown支持** - 支持数学公式渲染（KaTeX）

## 🛠️ 技术栈

- **前端框架**: Next.js 15.4.4 (React 19)
- **样式**: Tailwind CSS
- **动画**: GSAP
- **数学公式**: KaTeX
- **Markdown**: react-markdown
- **语言**: TypeScript

## 🚀 快速开始

### 环境要求

- Node.js 18+
- npm/yarn/pnpm

### 安装依赖

```bash
npm install
# 或
yarn install
# 或
pnpm install
```

### 启动开发服务器

```bash
npm run dev
# 或
yarn dev
# 或
pnpm dev
```

打开 [http://localhost:3000](http://localhost:3000) 查看应用。

### 构建生产版本

```bash
npm run build
npm run start
```

## 🐳 Docker 部署

本项目支持使用 Docker 和 Docker Compose 进行容器化部署。

### Docker 环境要求

- Docker
- Docker Compose

#### 使用 Docker 运行

##### 使用 本地 构建的镜像

1. 构建 Docker 镜像：

   ```bash
   docker build -t cogni-block-community .
   ```

2. 运行容器：

   ```bash
   docker run -p 3000:3000 cogni-block-community
   ```

##### 使用托管在 ghcr 上的镜像

```bash
docker run -p 3000:3000 ghcr.io/lirzh/cogniblock-community:latest
```

#### 使用 Docker Compose 部署

1. 启动服务：

   ```bash
   docker-compose up -d
   ```

2. 查看日志：

   ```bash
   docker-compose logs -f
   ```

3. 停止服务：

   ```bash
   docker-compose down
   ```

应用将在 <http://localhost:3000> 上运行。

## 🎯 主要功能

### 探索

- 浏览所有知识内容
- 按学科分类筛选
- 搜索功能
- 知识卡片和知识库切换

### 我的库

- 个人收藏的知识内容
- 学习进度跟踪

### 知识卡片

- 支持文本、图片、语音等多种形式
- Markdown 格式支持
- 数学公式渲染
- 快速预览和详细查看

## 📄 许可证

本项目采用 GPL3 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

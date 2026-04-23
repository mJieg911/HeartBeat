# 最最喜欢你 - 震撼重叠铺满版

一个炫酷的爱心动画网页，使用心形轨迹弹窗和烟花特效展示浪漫内容。

## 功能特点

- 心形轨迹弹窗动画
- 烟花爆炸特效
- 高密度重叠铺满效果
- 支持自定义最后一个弹窗内容
- 响应式设计，支持移动端

## 本地运行

```bash
# 安装依赖
npm install

# 本地开发
npm run dev
```

或者直接用浏览器打开 `index.html` 文件。

## 自定义内容

访问时可以通过 URL 参数自定义最后一个弹窗的内容：

- 使用 hash 参数：`https://your-domain.vercel.app/#我爱你`
- 使用 search 参数：`https://your-domain.vercel.app/?text=我爱你`
- 支持的参数名：`text`、`message`、`msg`

如果不传参数，默认显示"最最喜欢你"。

## 部署到 Vercel

### 方法一：通过 Vercel CLI

1. 安装 Vercel CLI：
```bash
npm install -g vercel
```

2. 登录 Vercel：
```bash
vercel login
```

3. 部署项目：
```bash
vercel
```

4. 生产环境部署：
```bash
vercel --prod
```

### 方法二：通过 GitHub 自动部署

1. 将代码推送到 GitHub 仓库
2. 访问 [Vercel 官网](https://vercel.com)
3. 点击 "New Project"
4. 导入你的 GitHub 仓库
5. Vercel 会自动检测配置并部署

### 方法三：直接拖拽部署

1. 访问 [Vercel 官网](https://vercel.com)
2. 将整个项目文件夹拖拽到页面上
3. 等待部署完成

## 项目结构

```
.
├── index.html             # 主页面
├── vercel.json            # Vercel 配置文件
├── package.json           # 项目配置
└── README.md              # 说明文档
```

## 技术栈

- 纯 HTML/CSS/JavaScript
- Canvas API (烟花特效)
- CSS3 动画
- 响应式设计

## 许可证

MIT

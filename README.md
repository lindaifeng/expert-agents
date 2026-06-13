# Expert Agents 专家提示词导航

> 215 位 AI 专家角色提示词，涵盖 16 大领域，完整中文翻译，即刻查阅使用。

## 在线访问

**https://lindaifeng.github.io/expert-agents/**

## 功能特性

- **215 位 AI 专家** — 涵盖工程、设计、营销、安全等 16 大领域
- **完整中文翻译** — 所有提示词内容严格翻译为中文，保留原始结构
- **模糊搜索** — 支持中文名称模糊匹配，快速找到目标专家
- **明暗主题** — 默认明亮模式，支持一键切换暗黑模式
- **Markdown 渲染** — 提示词内容使用 marked.js 渲染，完美呈现格式
- **网格卡片布局** — 响应式设计，桌面端 3-4 列，移动端自适应
- **弹窗详情** — 点击卡片弹出完整提示词内容
- **一键复制** — 支持复制 Markdown 格式的提示词内容
- **零外部依赖** — 单文件部署，marked.js 已内嵌，离线可用

## 专家分类

| 分类 | 数量 | 说明 |
|------|------|------|
| 工程开发 | 31 | 后端架构、前端开发、DevOps、数据工程等 |
| 设计创意 | 9 | UI/UX 设计、品牌管理、视觉叙事等 |
| 市场营销 | 36 | SEO、社交媒体、内容营销、增长黑客等 |
| 产品管理 | 5 | 产品经理、行为设计、趋势研究等 |
| 销售业务 | 9 | 销售教练、交易策略、管道分析等 |
| 信息安全 | 10 | 渗透测试、安全架构、威胁检测等 |
| 质量测试 | 8 | API 测试、性能基准、无障碍审计等 |
| 财务金融 | 5 | 财务分析、FP&A、税务策略等 |
| 运营支持 | 6 | 客服响应、合规审查、数据分析等 |
| 项目管理 | 7 | 项目协调、Jira 工作流、会议记录等 |
| 学术研究 | 5 | 心理学、人类学、叙事学等 |
| 游戏开发 | 5 | 游戏设计、关卡设计、技术美术等 |
| 地理信息 | 13 | GIS 分析、制图设计、空间数据等 |
| 付费媒体 | 7 | PPC 策略、社交媒体广告、追踪分析等 |
| 空间计算 | 6 | VisionOS、XR 开发、Metal 图形等 |
| 专业领域 | 53 | 商业策略、供应链、法律、医疗等 |

## 本地运行

```bash
# 方式 1：直接打开文件
open index.html

# 方式 2：使用 Python 服务器
python3 -m http.server 8080
# 访问 http://localhost:8080

# 方式 3：使用 Node.js
npx serve .
```

## 部署

### GitHub Pages（推荐）

1. Fork 本仓库，或创建新仓库并上传 `index.html`
2. 进入仓库 Settings → Pages
3. Source 选择 `main` 分支
4. 几分钟后访问 `https://你的用户名.github.io/仓库名/`

### Cloudflare Pages

1. 登录 Cloudflare Dashboard
2. Workers & Pages → Create application → Pages → Upload assets
3. 上传 `index.html`
4. 部署后获得 `*.pages.dev` 链接

### Vercel / Netlify

连接 GitHub 仓库，自动部署，无需配置。

## 项目结构

```
expert-agents/
└── index.html    # 单文件，包含 HTML + CSS + JS + 所有数据
```

## 技术栈

- 纯 HTML / CSS / JavaScript
- [marked.js](https://github.com/markedjs/marked) — Markdown 渲染（已内嵌）
- CSS Custom Properties — 明暗主题
- 无框架、无构建工具、无外部依赖

## 数据来源

所有专家提示词来自 [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) 开源仓库，已翻译为中文。

## 许可

MIT License

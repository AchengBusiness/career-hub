# Career-Hub | 职业工具导航站

> 四大职业方向的一站式工具导航门户
>
> One-stop career toolkit navigation portal for four career tracks

[![版本 Version](https://img.shields.io/badge/version-0.1.0-blue.svg)](./CHANGELOG.md)
[![许可证 License](https://img.shields.io/badge/license-MIT-green.svg)](./LICENSE)
[![GitHub Pages](https://img.shields.io/badge/deploy-GitHub%20Pages-blue.svg)](#部署--deploy)

---

## 目录 | Table of Contents

- [项目简介 | Introduction](#项目简介--introduction)
- [四大工具仓库 | Four Toolkit Repos](#四大工具仓库--four-toolkit-repos)
- [快速开始 | Quick Start](#快速开始--quick-start)
- [部署 | Deploy](#部署--deploy)
- [自定义 | Customization](#自定义--customization)
- [路线图 | Roadmap](#路线图--roadmap)
- [许可证 | License](#许可证--license)

---

## 项目简介 | Introduction

**Career-Hub** 是一个静态导航站点，汇聚四大职业方向的自动化工具集，帮助自媒体人、运营、销售和产品经理快速找到并使用所需工具。

部署在 GitHub Pages，零成本运行，永久可访问。

**Career-Hub** is a static navigation site aggregating automation toolkits across four career tracks, helping content creators, operators, salespeople, and product managers quickly find the tools they need.

Deployed on GitHub Pages, zero-cost, permanently accessible.

---

## 四大工具仓库 | Four Toolkit Repos

| 序号 | 仓库名 | 职业方向 | 说明 |
|------|--------|---------|------|
| 1 | [media-ops](https://github.com/AchengBusiness/media-ops) | 自媒体 Content Creator | 内容生成、多平台发布、定时调度、数据分析 |
| 2 | [ops-flow](https://github.com/AchengBusiness/ops-flow) | 运营 Operations | 工作流引擎、邮件自动化、数据采集、报告生成 |
| 3 | [sales-crm](https://github.com/AchengBusiness/sales-crm) | 销售 Sales | CRM管理、线索追踪、自动跟进、邮件外联 |
| 4 | [pm-toolkit](https://github.com/AchengBusiness/pm-toolkit) | 产品经理 Product Manager | 路线图、用户反馈、冲刺管理、PRD生成 |

---

## 快速开始 | Quick Start

```bash
# 克隆仓库 | Clone
git clone https://github.com/AchengBusiness/career-hub.git
cd career-hub

# 本地预览 | Local preview
# 方式1: 直接打开
open public/index.html

# 方式2: 使用任意HTTP服务器
npx serve public
```

---

## 部署 | Deploy

### GitHub Pages（推荐 | Recommended）

1. 推送代码到 GitHub
2. 进入仓库 Settings -> Pages
3. Source 选择 `main` 分支，文件夹选 `/public`
4. 等待部署完成
5. 访问 `https://AchengBusiness.github.io/career-hub/`

### 其他部署 | Alternative

- Vercel: 导入仓库即可自动部署
- Netlify: 拖拽 `public` 文件夹
- 任意静态托管服务

---

## 自定义 | Customization

编辑 `src/data/config.json` 来修改导航内容：

```json
{
  "title": "Career-Hub",
  "repos": [
    {
      "name": "media-ops",
      "title": "自媒体工具集 | Media Ops",
      "url": "https://github.com/AchengBusiness/media-ops",
      "description": "内容生成、多平台发布、数据分析"
    }
  ]
}
```

---

## 路线图 | Roadmap

- [x] v0.1.0 - 静态导航页面 | Static navigation page
- [ ] v0.2.0 - 响应式设计优化 | Responsive design
- [ ] v0.3.0 - 深色模式 | Dark mode
- [ ] v0.4.0 - 搜索功能 | Search feature
- [ ] v1.0.0 - 完整门户 | Full portal

---

## 许可证 | License

本项目采用 [MIT 许可证](./LICENSE) 开源。

This project is open-sourced under the [MIT License](./LICENSE).

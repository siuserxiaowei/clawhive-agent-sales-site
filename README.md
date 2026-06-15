# 企业级 AI Agent 竞品销售话术库

<!-- SIUSER-REPO-GUIDE:START -->
## Repository Guide

### What This Repository Does

Clawhive Agent 销售站：面向企业自动化与 AI Agent 服务的产品展示和转化页面。

English summary: Clawhive Agent sales site for presenting business automation and AI agent services.

### Online Entry Points

- GitHub repository: https://github.com/siuserxiaowei/clawhive-agent-sales-site
- Live / GitHub Pages: https://siuserxiaowei.github.io/clawhive-agent-sales-site/
- Default branch: `main`
- Primary language: `JavaScript`

### How To Read / Learn This Repository

1. 先读本 README，确认项目目标、在线入口和本地运行方式。
2. 打开上方 Live / GitHub Pages 链接，先从最终效果理解项目。
3. 按仓库目录从入口文件、数据文件、脚本和文档依次阅读。
4. 如果要修改内容，先小范围改动，再运行本 README 中的验证命令。

### Clone This Repository

```bash
git clone https://github.com/siuserxiaowei/clawhive-agent-sales-site.git
cd clawhive-agent-sales-site
```

### Run Or View Locally

```bash
python3 -m http.server 8000
```

然后打开 `http://127.0.0.1:8000/`。

### Repository Map

| Path | Purpose |
| --- | --- |
| `README.md` | 项目入口说明，先读这里。 |
| `index.html` | 静态站首页或页面入口。 |
| `docs/` | 文档或 GitHub Pages 输出目录。 |
| `assets/` | 图片、样式、字体或页面资源。 |
| `app.js` | 项目文件。 |
| `data.js` | 项目文件。 |
| `styles.css` | 项目文件。 |

### Maintenance Notes

- Keep this README in sync when the project purpose, live link, or run commands change.
- Prefer small, focused commits when changing code, data, or generated pages.
- Run the relevant build or validation command before publishing changes.
- If this is a generated/static archive, update the source data first, then regenerate the public files.

### Privacy And Safety

- Do not commit API keys, tokens, passwords, cookies, private URLs, or internal account data.
- Keep private source material out of public GitHub Pages output unless it has been explicitly cleared for publication.
- When in doubt, run a quick secret scan such as `rg -n "token|secret|password|access_key|authorization"` before pushing.
<!-- SIUSER-REPO-GUIDE:END -->

<!-- SIUSER-SEO-INTRO:START -->

## 项目介绍 / Project Introduction

**中文介绍**：Clawhive Agent 销售展示站，用网页讲清楚 AI Agent 服务、自动化价值和业务落地场景。

**English**: A sales website for Clawhive Agent services, explaining AI agent value, automation benefits, and business use cases.

**SEO 关键词 / SEO Keywords**: AI agent, sales site, business automation, landing page, Agent 服务

<!-- SIUSER-SEO-INTRO:END -->

这是一个可直接部署到 GitHub Pages 的静态交互网页，用于给销售/商务人员快速讲清楚“帝王蟹 ClawHive 与各家企业级 AI Agent 产品差在哪”。

## 文件结构

```text
.
├── index.html              # 页面主体
├── styles.css              # 页面样式
├── data.js                 # 竞品话术数据
├── app.js                  # 搜索、筛选、复制、对比逻辑
├── assets/market-map.svg   # 市场地图
├── docs/竞品话术清单.md      # Markdown 版话术备份
└── .nojekyll               # GitHub Pages 静态部署标记
```

## GitHub Pages 部署

1. 将本目录内所有文件放到 GitHub 仓库根目录，或放到仓库的 `docs/` 目录。
2. 在 GitHub 仓库进入 `Settings → Pages`。
3. `Source` 选择 `Deploy from a branch`。
4. 分支选择 `main`，目录选择 `/root`；如果放在 `docs/`，目录选择 `/docs`。
5. 保存后等待 Pages 生成公开访问地址。

## 内容说明

- 页面内容基于用户提供的《销售战斗卡》《竞品科普报告·修订版》《OpenClaw 生态深度分析报告》整理。
- 以“销售话术版”为目标，不写成技术白皮书。
- 每个竞品卡片均包含：一句话定位、三个核心优势、三个主要限制、对比帝王蟹 ClawHive 的差异化切入点。
- 修订版报告明确删除的未经验证硬数据未作为页面核心证据使用。

<!-- SIUSER-CONTACT:START -->

## 联系我 / Contact

想交流 AI 工具、内容自动化、SEO、私域增长或项目合作，可以扫码加我微信。

For collaboration on AI tools, content automation, SEO, private-domain growth, or product experiments, scan the WeChat QR code below.

<img src="https://raw.githubusercontent.com/siuserxiaowei/siuserxiaowei/main/assets/contact/wechat-qrcode.jpg" width="180" alt="WeChat QR code / 微信二维码" />

**关键词 / Keywords**: AI agent, sales site, business automation, landing page, AI tools, AI automation, GitHub Pages, SEO

<!-- SIUSER-CONTACT:END -->

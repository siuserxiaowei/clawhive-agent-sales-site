# 企业级 AI Agent 竞品销售话术库

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

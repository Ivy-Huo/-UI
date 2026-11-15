# Edge 智能中枢 · 驾驶舱三视图概览

云边端协同（Hub / Edge / Work）项目中的 **Edge 驾驶舱看板原型**，以单文件静态页面形式发布在 GitHub Pages。

## 在线预览

| 视图 | 地址 |
|---|---|
| 汇报概览 | https://ivy-huo.github.io/-UI/?view=report |
| 运营管理 | https://ivy-huo.github.io/-UI/?view=ops |
| 安全合规 | https://ivy-huo.github.io/-UI/?view=sec |

默认入口（汇报概览）：https://ivy-huo.github.io/-UI/

## 页面能力

- 三个视图各自是完整独立的自包含 SVG（1600×900），可直接导出 PNG。
- 支持「导出本视图 PNG」「一键生成全部概览图（合并长图）」「一键生成汇报包」（可打印或另存 PDF）。
- URL 参数 `?view=report|ops|sec`；追加 `&clean=1` 可隐藏工具栏，便于满屏截图。
- 单文件 HTML，无外部字体、图片或脚本依赖。

## 仓库文件

| 文件 | 说明 |
|---|---|
| `index.html` | 原型页面主体（自包含） |
| `.nojekyll` | 关闭 Jekyll，确保 HTML 原样发布 |
| `README.md` | 本说明 |

## 更新方式

修改本地源文件 `02_协同设计/edge驾驶舱看板原型.html` 后，把内容同步到本仓库 `main` 根目录的 `index.html` 并推送，Pages 会在约 1–2 分钟内自动重建。也可用 `publish_edge.py` 一条命令完成同步。

## 说明

页内所有指标为**演示数据**，非真实经营数据。设计主文档、竞品调研报告与功能点清单见本地交付包的 `README.md`。

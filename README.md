# ju-nei-ren-lao-k

局内人·老K ｜ 搞钱密道 — ima 付费知识库引流落地页

线上地址：https://muzhi-888.github.io/ju-nei-ren-lao-k/

## 页面结构

单文件静态页（`index.html`），无构建、无依赖，直接由 GitHub Pages 托管。

| 区块 | 锚点 | 内容 |
|---|---|---|
| 首屏 | `#top` | 品牌、口号、双 CTA、数据条 |
| ima 知识库 | `#kb` | 5 个主力库入口 |
| AI 工具 | `#tools` | 14 个开源仓库，带分类筛选（老K工具箱/搞钱/内容/提效） |
| 赛道雷达 | `#radar` | 10 个赛道搞钱仓库 |
| 投资 & 选号 | `#money` | 5 个 ima 分享库（黄金/选股/彩票×3） |
| CTA 横幅 | `#banner` | 关键词一键复制 |
| 关于 | `#about` | 人设说明与免责声明 |

## 维护要点

- 新增工具/赛道时，在对应 `<section>` 的 `.grid` 里加一张 `.card`；
  AI 工具区块的卡片要带 `data-cat`，取值：`laok` / `money` / `content` / `efficiency`。
- 所有 GitHub 链接指向 `muzhi-888` 名下**已存在**的仓库，新增前先确认仓库真实存在。
- 投资与选号内容属娱乐向，页面内已标注不构成投资建议。

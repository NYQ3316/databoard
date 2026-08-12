# databoard · 游戏数据埋点看板与命名规范

> 一个由 49 款体感 / 互动 / 体感健身 / 儿童益智类游戏组成的数据看板与埋点命名规范站点，统一托管在 **GitHub Pages** 上，供内部 PM、数据、研发、QA 共同查阅。

---

## 在线访问

| 入口 | URL |
| --- | --- |
| 首页（按上线月份分组） | <https://nyq3316.github.io/databoard/> |
| 命名规范总览（含 48 个项目命名页跳转） | <https://nyq3316.github.io/databoard/naming_standards> |
| 命名规范总览（独立版 · Clean URL 历史遗留） | <https://nyq3316.github.io/databoard/naming_standards_standalone.html> |

> GitHub Pages 对 *新增文件* 的 `.html` 直链偶有短暂 404，请优先使用 **Clean URL**（去掉 `.html`），或等待 1–2 分钟刷新。

---

## 仓库信息

| 项 | 内容 |
| --- | --- |
| 远程仓库 | `https://github.com/NYQ3316/databoard.git` |
| 默认分支 | `main` |
| Pages 源 | 分支根目录 |
| 技术栈 | 纯静态 HTML + Chart.js（CDN） |
| 总文件数 | 99 个 `.html` + `index.html` + 2 个命名规范页 + `README.md` |
| 当前看板数量 | 49 |
| 当前命名页数量 | 49 |

---

## 目录结构

```text
databoard/
├── index.html                          # 首页（卡片网格 · 按上线月份分组）
├── naming_standards.html               # 命名规范总览（新版本 · 内嵌 48 个项目入口）
├── naming_standards_standalone.html   # 命名规范总览（独立版 · 历史遗留入口）
├── README.md                           # 本文件
├── .nojekyll                           # 跳过 Jekyll 直接由 Pages 服务静态文件
│
├── 10XX_<游戏名>_analytics_dashboard.html   # 各项目的数据看板
└── 10XX_<游戏名>_naming.html                # 各项目的埋点事件 / 属性命名规范
```

### 页面分类约定

| 编号区间 | 类型 |
| --- | --- |
| 1001 – 1021 | 早期体感健身类项目 |
| 1023 – 1034 | 中期体感 / 互动类项目 |
| 1036 – 1049 | 儿童益智 / 节奏类项目 |
| 1051 – 1068 | 体感休闲 / 教育项目 |
| 1083 | 中文书名号版本（1083《决战世界之巅》） |

---

## 看板 & 命名页一览（49 个项目）

| # | 项目 ID | 游戏名 | 看板 | 命名页 |
| ---: | ---: | --- | :-: | :-: |
| 1 | 1001 | 篮球火 | [链接](https://nyq3316.github.io/databoard/1001_篮球火_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1001_篮球火_naming.html) |
| 2 | 1002 | 猫爪特工 | [链接](https://nyq3316.github.io/databoard/1002_猫爪特工_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1002_猫爪特工_naming.html) |
| 3 | 1003 | 怪兽大乱斗 | [链接](https://nyq3316.github.io/databoard/1003_怪兽大乱斗_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1003_怪兽大乱斗_naming.html) |
| 4 | 1005 | 光能守护者 | [链接](https://nyq3316.github.io/databoard/1005_光能守护者_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1005_光能守护者_naming.html) |
| 5 | 1007 | 炫舞宝贝 | [链接](https://nyq3316.github.io/databoard/1007_炫舞宝贝_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1007_炫舞宝贝_naming.html) |
| 6 | 1008 | 悦动英语单词 | [链接](https://nyq3316.github.io/databoard/1008_悦动英语单词_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1008_悦动英语单词_naming.html) |
| 7 | 1009 | 魔法塔防 | [链接](https://nyq3316.github.io/databoard/1009_魔法塔防_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1009_魔法塔防_naming.html) |
| 8 | 1010 | 功夫节拍 | [链接](https://nyq3316.github.io/databoard/1010_功夫节拍_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1010_功夫节拍_naming.html) |
| 9 | 1011 | 凯斯节奏 | [链接](https://nyq3316.github.io/databoard/1011_凯斯节奏_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1011_凯斯节奏_naming.html) |
| 10 | 1012 | 七十二变 | [链接](https://nyq3316.github.io/databoard/1012_七十二变_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1012_七十二变_naming.html) |
| 11 | 1013 | 海底世界 | [链接](https://nyq3316.github.io/databoard/1013_海底世界_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1013_海底世界_naming.html) |
| 12 | 1016 | 悦动儿歌 | [链接](https://nyq3316.github.io/databoard/1016_悦动儿歌_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1016_悦动儿歌_naming.html) |
| 13 | 1017 | 天天拳击 | [链接](https://nyq3316.github.io/databoard/1017_天天拳击_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1017_天天拳击_naming.html) |
| 14 | 1018 | 镜之修行 | [链接](https://nyq3316.github.io/databoard/1018_镜之修行_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1018_镜之修行_naming.html) |
| 15 | 1019 | 客厅运动会 | [链接](https://nyq3316.github.io/databoard/1019_客厅运动会_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1019_客厅运动会_naming.html) |
| 16 | 1020 | 家庭健康体能测试档案 | [链接](https://nyq3316.github.io/databoard/1020_家庭健康体能测试档案_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1020_家庭健康体能测试档案_naming.html) |
| 17 | 1021 | 动物指挥家 | [链接](https://nyq3316.github.io/databoard/1021_动物指挥家_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1021_动物指挥家_naming.html) |
| 18 | 1023 | 唐唐甜品屋 | [链接](https://nyq3316.github.io/databoard/1023_唐唐甜品屋_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1023_唐唐甜品屋_naming.html) |
| 19 | 1024 | 蟹蟹大冒险 | [链接](https://nyq3316.github.io/databoard/1024_蟹蟹大冒险_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1024_蟹蟹大冒险_naming.html) |
| 20 | 1025 | 体感卡丁车 | [链接](https://nyq3316.github.io/databoard/1025_体感卡丁车_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1025_体感卡丁车_naming.html) |
| 21 | 1026 | 小鳄鱼的水果乐园 | [链接](https://nyq3316.github.io/databoard/1026_小鳄鱼的水果乐园_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1026_小鳄鱼的水果乐园_naming.html) |
| 22 | 1028 | 流光庭径 | [链接](https://nyq3316.github.io/databoard/1028_流光庭径_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1028_流光庭径_naming.html) |
| 23 | 1029 | 跳房子 | [链接](https://nyq3316.github.io/databoard/1029_跳房子_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1029_跳房子_naming.html) |
| 24 | 1030 | 莱美-生来悦动 | [链接](https://nyq3316.github.io/databoard/1030_莱美-生来悦动_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1030_莱美-生来悦动_naming.html) |
| 25 | 1031 | 网球大师 | [链接](https://nyq3316.github.io/databoard/1031_网球大师_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1031_网球大师_naming.html) |
| 26 | 1032 | 斑马百科 | [链接](https://nyq3316.github.io/databoard/1032_斑马百科_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1032_斑马百科_naming.html) |
| 27 | 1034 | 巅峰骑士 | [链接](https://nyq3316.github.io/databoard/1034_巅峰骑士_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1034_巅峰骑士_naming.html) |
| 28 | 1036 | 超级飞侠 | [链接](https://nyq3316.github.io/databoard/1036_超级飞侠_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1036_超级飞侠_naming.html) |
| 29 | 1037 | 超级贪吃鱼 | [链接](https://nyq3316.github.io/databoard/1037_超级贪吃鱼_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1037_超级贪吃鱼_naming.html) |
| 30 | 1039 | 萌鸡小队脑力课堂 | [链接](https://nyq3316.github.io/databoard/1039_萌鸡小队脑力课堂_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1039_萌鸡小队脑力课堂_naming.html) |
| 31 | 1040 | 小伴龙与动物朋友们 | [链接](https://nyq3316.github.io/databoard/1040_小伴龙与动物朋友们_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1040_小伴龙与动物朋友们_naming.html) |
| 32 | 1041 | 萝卜蹲 | [链接](https://nyq3316.github.io/databoard/1041_萝卜蹲_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1041_萝卜蹲_naming.html) |
| 33 | 1042 | 贪心大作战 | [链接](https://nyq3316.github.io/databoard/1042_贪心大作战_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1042_贪心大作战_naming.html) |
| 34 | 1043 | 森林树乐园 | [链接](https://nyq3316.github.io/databoard/1043_森林树乐园_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1043_森林树乐园_naming.html) |
| 35 | 1044 | 啪叽啪叽叠塔对决 | [链接](https://nyq3316.github.io/databoard/1044_啪叽啪叽叠塔对决_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1044_啪叽啪叽叠塔对决_naming.html) |
| 36 | 1045 | 摇摆掘金车 | [链接](https://nyq3316.github.io/databoard/1045_摇摆掘金车_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1045_摇摆掘金车_naming.html) |
| 37 | 1046 | 一滚到底 | [链接](https://nyq3316.github.io/databoard/1046_一滚到底_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1046_一滚到底_naming.html) |
| 38 | 1048 | 我家小猫 | [链接](https://nyq3316.github.io/databoard/1048_我家小猫_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1048_我家小猫_naming.html) |
| 39 | 1049 | 弹珠迷城 | [链接](https://nyq3316.github.io/databoard/1049_弹珠迷城_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1049_弹珠迷城_naming.html) |
| 40 | 1051 | 提线木偶 | [链接](https://nyq3316.github.io/databoard/1051_提线木偶_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1051_提线木偶_naming.html) |
| 41 | 1052 | 扭扭橡皮艇 | [链接](https://nyq3316.github.io/databoard/1052_扭扭橡皮艇_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1052_扭扭橡皮艇_naming.html) |
| 42 | 1053 | 悦钓时光 | [链接](https://nyq3316.github.io/databoard/1053_悦钓时光_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1053_悦钓时光_naming.html) |
| 43 | 1055 | 超智能工程机 | [链接](https://nyq3316.github.io/databoard/1055_超智能工程机_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1055_超智能工程机_naming.html) |
| 44 | 1058 | 深空突袭 | [链接](https://nyq3316.github.io/databoard/1058_深空突袭_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1058_深空突袭_naming.html) |
| 45 | 1061 | 奇妙萌可 | [链接](https://nyq3316.github.io/databoard/1061_奇妙萌可_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1061_奇妙萌可_naming.html) |
| 46 | 1062 | 愿望喵喵跑酷 | [链接](https://nyq3316.github.io/databoard/1062_愿望喵喵跑酷_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1062_愿望喵喵跑酷_naming.html) |
| 47 | 1063 | 墨韵寻诗 | [链接](https://nyq3316.github.io/databoard/1063_墨韵寻诗_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1063_墨韵寻诗_naming.html) |
| 48 | 1068 | 完美定格 | [链接](https://nyq3316.github.io/databoard/1068_完美定格_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1068_完美定格_naming.html) |
| 49 | 1083 | 决战世界之巅 | [链接](https://nyq3316.github.io/databoard/1083《决战世界之巅》_analytics_dashboard.html) | [链接](https://nyq3316.github.io/databoard/1083_决战世界之巅_naming.html) |

> 备注：1044 目录下还存在一份历史遗留文件 `1044_小伴龙与动物朋友们_analytics_dashboard.html`，只是无人引用的冗余副本；如需清理可另开 PR 删除。

---

## 内容简介

### 1. 首页 `index.html`

- 按上线月份对项目卡片进行分组，渐变色背景
- 每张卡片显示：项目 ID、名称、上线月份、可点击跳转看板
- 顶部统计栏：项目总数 / 在线项目数 / 最近更新时间
- 单独保留一个常驻入口指向命名规范总览

### 2. 命名规范总览 `naming_standards.html`

- 内嵌全部 48 个项目的命名页跳转入口
- 每个项目的命名页通常包含：
  - 该游戏的核心事件（`event_id`）列表
  - 事件通用属性 / 私有属性（`property`）定义
  - 数据类型、是否必传、示例值等
- 提供返回首页的链接按钮

### 3. 看板页 `*_analytics_dashboard.html`

- 由内嵌 JS + Chart.js CDN 渲染
- 常见图表：总对局数、人次分布、留存曲线、付费转化、动作明细表等
- 数据以静态数组形式内嵌在 `<script>` 中，方便离线 / 受限网络环境下访问

---

## 本地预览

仓库 100% 静态，无需构建，任意 HTTP 服务即可：

```bash
# 方式 1：Python
cd databoard
python -m http.server 8000
# 浏览器打开 http://localhost:8000/

# 方式 2：Node
npx serve .

# 方式 3：直接双击 index.html
# 注意 Chrome 对 file:// 下的 CDN 请求会拦截部分 JS，本地推荐方式 1
```

---

## 部署 / 更新流程

本仓库通过 **GitHub Pages** 自动部署：推送 `main` 后通常 1–2 分钟生效。

```bash
# 1. 拉取
git pull origin main

# 2. 新增 / 修改 / 删除文件后
git add -A
git commit -m "feat: 新增 10XX 项目看板"

# 3. 推送即发布
git push origin main
```

约定式提交前缀：`feat` / `fix` / `refactor` / `chore` / `docs` / `style`。

---

## 最近更新日志

| 日期 | 提交 | 说明 |
| --- | --- | --- |
| 2026-08-09 | `233d385` | 修正首页及命名文件的 `naming_standards` 链接为 Clean URL |
| 2026-08-09 | `662ecac` | 同步 1037 超级贪吃鱼看板 & 命名页，修复 1007 / 1044 / 1051 命名 `total_score` 类型 |
| 2026-08-03 | `b7734e4` | 同步调整后的首页并修正命名规范入口 |
| 2026-07-31 | `731d9e3` | 修复 1041 萝卜蹲看板 Chart.js 依赖（本地 → CDN） |
| 2026-07-31 | `5d44eef` | 同步 1041 萝卜蹲页面 |
| 2026-07-30 | `4423fab` | 同步 1061 奇妙萌可页面并添加入口 |
| 2026-07-30 | `24c4d90` | 同步 1031 网球大师页面并添加首页入口 |
| 2026-07-28 | `ad5bf66` | 首页卡片按上线月份重新分组 |
| 2026-07-28 | `5250ab4` | 首页添加 1029 跳房子看板入口 |

---

## 贡献与反馈

- 入口 / 链接异常、看板图表无数据 → 请在对应的项目卡片下留言或直接提 Issue
- 新增项目需提供：`10XX_<名称>_analytics_dashboard.html` + `10XX_<名称>_naming.html`
- 同一项目 ID 下命名页与看板的 `event_id` / `property` 定义须保持一致

---

_Last updated: 2026-08-09_

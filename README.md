<p align="center">
  <strong>中文</strong> · <a href="https://gitcode.com/LLLAAAAA/dsh-dream-skin/blob/main/docs/i18n/README.en.md">English</a> · <a href="https://gitcode.com/LLLAAAAA/dsh-dream-skin/blob/main/docs/i18n/README.ja.md">日本語</a> · <a href="https://gitcode.com/LLLAAAAA/dsh-dream-skin/blob/main/docs/i18n/README.ko.md">한국어</a> · <a href="https://gitcode.com/LLLAAAAA/dsh-dream-skin/blob/main/docs/i18n/README.es.md">Español</a> · <a href="https://gitcode.com/LLLAAAAA/dsh-dream-skin/blob/main/docs/i18n/README.fr.md">Français</a> · <a href="https://gitcode.com/LLLAAAAA/dsh-dream-skin/blob/main/docs/i18n/README.de.md">Deutsch</a> · <a href="https://gitcode.com/LLLAAAAA/dsh-dream-skin/blob/main/docs/i18n/README.ru.md">Русский</a>
</p>

<div align="center">

# dsh-dream-skin 🔮

[![npm](https://img.shields.io/npm/v/dsh-dream-skin.svg?style=for-the-badge&logo=npm&logoColor=white&label=dsh-dream-skin&color=cb3837)](https://www.npmjs.com/package/dsh-dream-skin)
[![downloads / month](https://img.shields.io/npm/dm/dsh-dream-skin.svg?style=for-the-badge&label=installs%2Fmo&color=0a6aa1)](https://www.npmjs.com/package/dsh-dream-skin)
![DSH hosts: Web | Desktop](https://img.shields.io/badge/DSH_hosts-Web%20%7C%20Desktop-6f5bd0?style=for-the-badge)
![8 original themes](https://img.shields.io/badge/8%20original-themes-f08a5a?style=for-the-badge)
![8 languages](https://img.shields.io/badge/8-languages-2fa37a?style=for-the-badge)
[![license MIT](https://img.shields.io/npm/l/dsh-dream-skin.svg?style=for-the-badge&label=MIT&color=888)](https://gitcode.com/LLLAAAAA/dsh-dream-skin/blob/main/LICENSE)

> HOL 验证与 DSH Insights 收录仍按旧 GitHub 坐标索引，账号封禁后不再作为徽章展示；新主机重新登记完成前不对外声称已验证（见「版本 11.4.2」）。

**为 DeepSeek Harness 换上一张克制、清透、有质感的「脸」。**

原生换肤 · 背景壁纸 · 强调色 · 主题包 —— 一条 `--dsw-*` token 生态内的优雅实现。装一次，用很久。

> **写代码的地方，可以很安静。**

| 🎨 8 套原创主题 | 🖼️ 壁纸 + 弥散光 | 🎯 克制的强调色 | 📦 主题包可分享 |
|---|---|---|---|

> 1 行安装 · 纯原生（无注入/不改安装包）· 不因 DSH 更新失效

</div>

---

## 🎮 两种玩法，一条插件都给你

<table>
  <tr>
    <td align="center" width="50%"><h3>🪄 玩法一：开箱即用的优雅</h3></td>
    <td align="center" width="50%"><h3>🧱 玩法二：随你掌控的 DIY</h3></td>
  </tr>
  <tr>
    <td>内置 <b>8 套设计师调校的预设皮肤</b>（Mirage 幻梦系列），浅色 / 深色兼顾，每套自带专属弥散光背景。<br/><b>戴上即高级，不用任何调参。</b></td>
    <td>在预设之上，你还能 <b>换壁纸（本地图 / URL / 渐变）</b>、<b>叠加强调色 Accent</b>、<b>拖入或分享一个主题包</b>，内部每个 token 都能摸到。<br/><b>想要的样子，自己捏。</b></td>
  </tr>
</table>

两种玩法分层独立、互不干扰：预设皮肤决定「材质与底色」，DIY 一层是纯叠加（`overrideTokens`），随开随关、一键还原。

---

## 📸 界面预览

> 首屏是 DeepSeek Harness Desktop **0.2.2-rc.3** 在**宿主默认弥散光壁纸**下的新会话实机截图（2026-11-14 直出，裁掉含私人工作区名的侧栏，未合成、未修图）。此前那张沿用旧出厂壁纸的预览图含真人照片，被 GitCode 按内容拒绝预览（`raw/main` 302 跳到 `cannot_preview.svg`），已撤下；现在这张不含人物、实机直出，`raw/main` 实测 `200 image/png` 且与仓库文件逐字节相同。下方是设置里「个性化皮肤」分节的实机截图，八套皮肤的配色预览见下一节。

<p align="center">
  <img src="https://raw.gitcode.com/LLLAAAAA/dsh-dream-skin/raw/main/docs/screenshots/hero-default-wallpaper.png" alt="宿主默认弥散光壁纸下的 DeepSeek Harness Desktop 新会话实机截图" width="100%"/>
</p>

<p align="center">
  <img src="https://raw.gitcode.com/LLLAAAAA/dsh-dream-skin/raw/main/docs/screenshots/settings.png" alt="设置中的「个性化皮肤」分节" width="72%"/>
</p>

---

## 🎨 玩法一：8 套预设皮肤（Mirage 幻梦系列）

> **开箱即用的优雅。** 在 **设置 → 个性化皮肤** 一键切换。下列预览由各皮肤的**真实 token + 专属弥散光背景**生成——所见即所得，点开可放大查看精致材质。

<table>
  <tr>
    <td align="center"><a href="https://raw.gitcode.com/LLLAAAAA/dsh-dream-skin/raw/main/docs/previews/abyss.png"><img src="https://raw.gitcode.com/LLLAAAAA/dsh-dream-skin/raw/main/docs/previews/abyss.png" width="230" alt="abyss"/></a><br/><b>abyss</b> · 🕶️ 沉静蓝<br/><sub>深海蓝黑底，唯一一束靛蓝高光；弥散光取深水反弹</sub></td>
    <td align="center"><a href="https://raw.gitcode.com/LLLAAAAA/dsh-dream-skin/raw/main/docs/previews/aurora.png"><img src="https://raw.gitcode.com/LLLAAAAA/dsh-dream-skin/raw/main/docs/previews/aurora.png" width="230" alt="aurora"/></a><br/><b>aurora</b> · 🌌 极光青<br/><sub>冷青主调，强调色转出成功绿带，信号色永不撞车</sub></td>
    <td align="center"><a href="https://raw.gitcode.com/LLLAAAAA/dsh-dream-skin/raw/main/docs/previews/nebula.png"><img src="https://raw.gitcode.com/LLLAAAAA/dsh-dream-skin/raw/main/docs/previews/nebula.png" width="230" alt="nebula"/></a><br/><b>nebula</b> · 🪐 星云紫<br/><sub>星云尘埃紫，弹层与气泡同源渐变，朦胧而有序</sub></td>
    <td align="center"><a href="https://raw.gitcode.com/LLLAAAAA/dsh-dream-skin/raw/main/docs/previews/ember.png"><img src="https://raw.gitcode.com/LLLAAAAA/dsh-dream-skin/raw/main/docs/previews/ember.png" width="230" alt="ember"/></a><br/><b>ember</b> · 🔥 余烬橙<br/><sub>唯一暖色暗皮肤：焦琥珀 + 深可可底，暖而不脏</sub></td>
  </tr>
  <tr>
    <td align="center"><a href="https://raw.gitcode.com/LLLAAAAA/dsh-dream-skin/raw/main/docs/previews/midnight.png"><img src="https://raw.gitcode.com/LLLAAAAA/dsh-dream-skin/raw/main/docs/previews/midnight.png" width="230" alt="midnight"/></a><br/><b>midnight</b> · 🌚 子夜黑<br/><sub>刻意消色差的 OLED 纯黑，最克制的沉浸</sub></td>
    <td align="center"><a href="https://raw.gitcode.com/LLLAAAAA/dsh-dream-skin/raw/main/docs/previews/ivory.png"><img src="https://raw.gitcode.com/LLLAAAAA/dsh-dream-skin/raw/main/docs/previews/ivory.png" width="230" alt="ivory"/></a><br/><b>ivory</b> · 📐 iOS 扁平<br/><sub>暖纸感画布 + iOS 蓝，白阶梯精排不刺眼</sub></td>
    <td align="center"><a href="https://raw.gitcode.com/LLLAAAAA/dsh-dream-skin/raw/main/docs/previews/mist.png"><img src="https://raw.gitcode.com/LLLAAAAA/dsh-dream-skin/raw/main/docs/previews/mist.png" width="230" alt="mist"/></a><br/><b>mist</b> · 🧊 干净明亮<br/><sub>唯一真半透明液态玻璃：六层 alpha 表面，模糊 8px</sub></td>
    <td align="center"><a href="https://raw.gitcode.com/LLLAAAAA/dsh-dream-skin/raw/main/docs/previews/rose.png"><img src="https://raw.gitcode.com/LLLAAAAA/dsh-dream-skin/raw/main/docs/previews/rose.png" width="230" alt="rose"/></a><br/><b>rose</b> · 🌸 Material 粉<br/><sub>玫瑰纸感 + 品牌洋红，红色信号仍归红色</sub></td>
  </tr>
</table>

> 浅色 / 深色兼顾：`mist`、`ivory`、`rose` 为浅色系，其余为深色系。
>
> **每套皮肤自带专属默认参数**（弥散光浓度 / 模糊 / 侧栏与输入框透明度 / 弹窗透明度 / 玻璃材质）——
> 切到哪套，哪套就是它的最佳状态；你自己调过的参数不会被覆盖。8 套皮肤全部通过 229 项可测质量门（217 项调色门 + 12 项工艺门）
> （OKLCH 感知明度阶梯、三级文字对比度 WCAG 2.1 + APCA 双达标、信号色相分离、跨皮肤可区分度）。
> 不喜欢预设？往下看**玩法二**。

---

## 🧱 强大 DIY 空间（玩法二）

> 预设皮肤之外，dsh-dream-skin 还给你一套完整的自定义体系——想捏出独一无二的工作区，从这里开始。

| 能力 | 玩法二 · 你能做什么 |
|------|------|
| 🖼️ **自定义壁纸 2.0** | 本地图 / **图片 URL** / **渐变预设**；附带**透明度 / 模糊 / 填充方式**（裁剪填充 · 完整显示 · 模糊填充；后两档里竖图自动并排平铺），每套皮肤还**自动建议**一张渐变，可**自动弱化**（壁纸不透明度最高 45%） |
| 🌈 **每用户强调色 Accent** | 为当前皮肤叠加自定义品牌强调色（`overrideTokens` 层，不动皮肤本身），**12 个典型色块一键选色** + 选色盘 + 随机 + 恢复主题色 |
| 📦 **主题包导入 / 导出 / 分享** | 一个 `*.dsh-theme.json` = manifest + 全套 tokens，可**导入文件**、**一键应用**、**复制分享链接**（编码进 URL hash） |
| 🪟 **弹窗不透明度** | 滑块控制下拉菜单 / 浮层 / 弹窗的底填充透明度，跟随持久化保存；凡用「弹层底色」令牌铺底的面（设置面板、插件管理、轨迹图 tooltip、卡片浮层等）共享一层 92% 可读性下限，滑杆拉到底也不读穿；下拉菜单与遮罩两条腿仍是全量程 |
| 🧩 **本地主题包库** | 导入的主题包集中展示，**应用 / 收藏 / 移除** 一键完成 |
| 🎲 **随机换一个（surprise me）** | 随机换一个和你当前不同的主题；**收藏**喜欢的皮肤快速切换 |
| 🧹 **恢复出厂设置（11.4.0）** | 在「导入与导出」底部，两段式确认（点两下才算数，旁边有取消）。把所有**设置项**改回出厂值——滑杆、开关、皮肤、强调色、材质、壁纸数值与取景，**壁纸链接本身也回到出厂那张（必应每日）**；**导入的主题包、收藏、壁纸文件夹路径与轮播列表一律不动**，因为那是你带进来的内容，不是"默认"该覆盖的东西。低功耗开关回到「自动跟随系统」 |
| ✅ **校验 + 回滚** | 导入时校验格式 / 必填 token / 颜色合法性；失败或移除时安全回退，不做破坏性更改 |

> 一切都叠加在预设之上，**随开随关、一键还原**到 DSH 内置外观——大胆去试，不会弄坏什么。

---

## ⚡ 一句话安装

**复制下面这句话给你的 DSH，它自己会装好一切：**

> 请帮我安装 dsh-dream-skin 换肤插件（https://gitcode.com/LLLAAAAA/dsh-dream-skin 或 npm 的 dsh-dream-skin），装完告诉我如何重启 DSH Web。

不想麻烦 Agent？命令行一条：

```sh
dsh plugin --profile web add dsh-dream-skin && dsh web
```

> 🚀 **现已发布到 npm！** 装好 DSH 后，一条命令即可安装，无需 clone。

> **纯原生接入**，无注入、不改二进制、不因客户端更新失效。

---

## 🏆 为什么值得用（vs 同类 DSH 主题插件）

> 换个赛道看：同类插件要么是把一套现成色板移植过来（好看，但配置只有一个开关）、要么是锁死单一美学的定制款、
> 要么专注把外部壁纸搬进来。我们把换肤做成**一整套可调的材质与配色系统**——追求的不是「更花」，
> 而是「更准、更克制、更耐看」，像一块反复推敲的玻璃。**审美 + 可调性是我们的护城河。**

| 能力 | 本插件 | [dsh-catppuccin-theme](https://github.com/NoNameLeGo/dsh-catppuccin-theme)（色板移植） | [dsh-theme-mineradio](https://github.com/dhicoc/dsh-theme-mineradio)（单一美学定制） | [dsh-wallpaper-engine](https://github.com/elysia395/dsh-wallpaper-engine)（壁纸引擎 + 液态玻璃 UI） |
|------|:---:|:---:|:---:|:---:|
| **8 套原创设计**（非现成色板移植，原创 token + 弥散光） | ✅ | ❌ (4 套 Catppuccin 官方色板) | ❌ (1 套香槟金美学) | ❌ |
| **毛玻璃 / 液态玻璃双材质**一键切换 | ✅ | 部分（固定玻璃质感） | ❌ | ❌ |
| **输入框 / 弹窗独立透明度滑杆** | ✅ | ❌ | ❌ | 部分（设置窗口 / 浮层 / 左侧栏 / 标题栏各有独立透明度与模糊；输入卡片与气泡可独立配颜色与保真度，透明度走全局） |
| **开箱即用的出厂配置**（装完重启就是调好的样子） | ✅ | ❌ | ✅（本身即成品） | 部分（出厂玻璃默认 + 7 份玻璃预设；无出厂壁纸 / 皮肤） |
| 自定义壁纸 + 透明度/模糊 | ✅ | ❌ | ❌ | ✅（核心能力） |
| **壁纸 2.0**（URL / 渐变预设 / 每皮肤建议 / 自动弱化 / 必应每日 + 定时更新） | ✅ | ❌ | ❌ | 部分（本地图片 / 视频上传 + 自动轮播定时切换 + 适配模式；无 URL / 渐变预设 / 必应每日） |
| **每用户强调色 Accent**（叠加层，不动皮肤本身） | ✅ | ❌ | ❌ | 部分（6 预设 + 自定义主题色，驱动按钮 / 开关 / 链接 / 导航选中 / 滑块 / 玻璃高光；无「皮肤叠加层」概念） |
| **主题包导入/导出 + 分享链接**（JSON，无代码分发） | ✅ | ❌ | ❌ | 部分（字体集与玻璃预设可导出 / 导入 JSON；无分享链接） |
| 本地主题包库 + 收藏 + 随机换 | ✅ | ❌ | ❌ | ❌ |
| **两代宿主兼容 + 运行时能力探测**（宿主换代自动降级不报错） | ✅ | 未知 | 未知 | 部分（单一开放 peer 区间覆盖 0.1.5-rc.1+ 与 0.2.x 两条宿主线；有宿主形态 / 能力探测与局部降级；内核下限 0.1.5-rc.1 为硬要求） |
| 校验 + 回滚（不做破坏性更改） | ✅ | 部分 | — | 部分 |

> **一句话**：想要 Catppuccin 的品牌色、mineradio 的氛围感？本插件的主题包系统都能做出来或叠出来——
> 反过来不成立。

---

## ✨ 功能一览

| 能力 | 说明 |
|------|------|
| 🎨 **8 套主题预设（Mirage 幻梦）** | 在 **设置 → 个性化皮肤** 一键切换，浅色 / 深色兼顾 |
| 🖼️ **自定义壁纸** | 上传本地图（自动压缩 ≤2MB），调节**透明度 / 模糊 / 填充方式**（裁剪填充 / 完整显示 / 模糊填充）；选中图片后可再调**取景**（水平/垂直偏移 ±100%、缩放 50–300%，偏移以视口为单位，图片可以整张移出画面） |
| 🧊 **玻璃材质（毛玻璃 / 液态玻璃）** | 一键切换玻璃质感，透明度滑杆**越右越透**；模糊一个旋钮同时驱动壁纸与玻璃表面 |
| 🪫 **低功耗模式** | 设置 → 玻璃效果里一个勾选：关闭全部玻璃模糊与壁纸模糊，把大块半透明面变成平涂。给「两块窗口同开就掉帧 / GPU 占用高」的机器一个开关（issue #110）；**三态**：没动过勾选 = 自动跟随系统的「减少透明度」（macOS 辅助功能 → 显示 → 减少透明度），勾过 = 固定住你的选择，行上可「交还给自动」。#110 的 M4 实测：空闲 GPU 23% → 11%，快速滚动 75-80% → 60-65% |
| 🖼️ **开箱即用的出厂配置** | 首次安装即带完整美化配置：星云皮肤 + 内置壁纸 + 调好的玻璃数值，装完重启就能用 |
| 🌤️ **必应每日壁纸（预置）** | 「背景与壁纸」选「固定图片 → 图片链接」时预填必应每日一图接口，点「保存」即可（重复点会**强制重新拉图**，不会被浏览器缓存挡回旧图）；也支持任意图片 URL + 定时更新缓存 |
| 🔁 **壁纸轮换** | 「背景形式」选「图片轮播」后，图片来源可在**图片链接**（最多 20 条 http/https 图片链接，每行一条）或**本地文件夹**（填文件夹路径，读这一层和往下最多三层真实子文件夹里的 jpg / png / webp / gif / avif / bmp，不含 HEIC、SVG、隐藏文件夹和符号链接；新放进去的照片自动加入）之间选一个图源，按 5 分钟到 7 天的间隔顺序或随机切换（文件夹图源下顺序即「按目录名字」：先播文件夹自己的图，再按名字逐个子文件夹播完），也可点「切换到下一张」。文件夹由插件的宿主部分读取，只能读到所选文件夹里的图片。坏链接或打不开的图片只丢它自己；窗口隐藏时不切换，回到前台补上；默认关闭（issue #61） |
| 🔤 **内层不透明** | 卡片、输入框、消息气泡不被壁纸盖住，可读性优先 |
| ↩️ **默认还原** | 一键回到 DSH 内置外观（跟随系统） |
| 💾 **三层持久化** | 皮肤与壁纸存 `localStorage` **+ 宿主侧 `dream-skin.json`**，刷新不丢；**桌面版每次换端口、重启也不丢** |

---

## 🔬 合成器预算（issue #110）

<details>
<summary>⌄ 展开本节</summary>

模糊不是"看着更重"——**每一块磨砂面都是一次离屏合成**，两块窗口同开就是两倍。所以这一项有数可查：

```sh
npm run compositor:audit        # 逐处：行号 / 模糊半径 / 所在选择器
```

（在仓库里跑——npm 包只带运行时，不含 scripts/）

当前发货的浏览器半边实测：**6 块 `backdrop-filter` 面板**（宿主的提问卡 24px、待办/队列坞 20px；我方的模态卡 14px、输入框 14px、`/` 命令面板 14px、液态玻璃 34px；另有 2 条 `none` 低功耗守卫，审计合计 8 条声明）、**40 处 radial-gradient**、**2 个 `requestAnimationFrame` 循环**，外加**壁纸层的全屏 `filter: blur()`**（"模糊填充"时还有一层更厚的 bleed 光晕）——最后这笔是最大的一层，它由 JS 写在行内样式上，**不在样式表里**，所以只读 CSS 的审计会把它漏掉（第一版就是这么漏的）。这些数字由 `tests/compositor_budget.test.cjs` 看住：多一块、厚一档，都要在 diff 里改预算表并写理由。

**它能证明什么**：这个版本**声明**了几块面板、每块多厚，以及低功耗开关是否真的覆盖了它们（含伪元素与壁纸层）。
**它不能证明什么**："你的机器此刻合成了几块"——那取决于窗口数、外接屏、驱动，以及当前挂了哪些面板。

**觉得卡，先开低功耗**（设置 → 玻璃效果）：它会把页面上**每一个** `backdrop-filter`（含 `*::before` / `*::after`）和壁纸那层模糊一起关掉。这是本插件为"两块窗口同开就掉帧"准备的唯一开关。

**报性能 issue 时最有用的三样**：① 开 / 关低功耗各一次的实际感受；② `chrome://gpu` 里 Compositing 那一段；③ 同时开了几个窗口、几块屏。维护者手上没有 M4 机器——静态那一半我们能自己量，动态那一半只能靠你那边。

</details>

## 🧩 它是什么形式的插件

<details>
<summary>⌄ 展开本节</summary>

**它是 DeepSeek Harness 的标准「双面插件」（`dsh-plugin`）——加载和用法与官方 `ui-theme` 完全一致。**

DeepSeek Harness 的口号是「一切皆插件」：模型、工具、沙箱、会话、UI，乃至 Agent Loop 本身都是插件。
`dsh-dream-skin` 的本质就是把「换肤」做成一个和官方 UI 包**同构**的 npm 包：

```text
            ┌────────────── dsh-dream-skin（标准 dsh-plugin / 双面插件）──────────────┐
            │  dsh.bundle   → cordis.patch.yml 插入 dream-skin 入口   (host 半边)     │
            │  dsh.client   → lib/client.js（浏览器 bundle）          (浏览器半边)     │
            └─────────────────────────────────────────────────────────────────────────┘
```

- **安装命令 = 官方唯一安装命令**：`dsh plugin --profile web add dsh-dream-skin`
- **官方桌面版（DSH Desktop）不能用命令行装**：宿主 CLI 里写死了 `profile === "desktop"` 直接报错
  （`error: profile "desktop" is managed exclusively by the Electron application`，本机在 `dsh/lib/bin.js` 读到该分支）。
  两条走得通的路：① 在应用内的插件管理界面装；② 在该 profile 目录里手工
  `pnpm add dsh-dream-skin@<确切版本号>`（实测 2.3 秒通过，pnpm 会自行把该版本追加进 `minimumReleaseAgeExclude`）。
  **版本号必须写死**：老 profile 的 `^9.x` 按 semver 覆盖不到 10.x，而发布 24 小时内不带版本号的命令会被 pnpm 冷静期退回旧版。
- **调用的是官方扩展点**：`ctx.theme`（注册主题）、`ctx.theme.overrideTokens`（叠加层）、
  `ctx.slots`（把 UI 挂进独立的 **设置 → 个性化皮肤** 分节）。
- **manifest 契约与官方一致**：`dsh.bundle` + `dsh.client` + `exports["./client"]`。

也就是说：**你装的不是一个旁门左道的脚本，而是 DSH 官方插件体系里的标准皮肤插件。**

---

</details>

## ⚡ 快速开始（3 步）

```sh
# 1. 安装
dsh plugin --profile web add dsh-dream-skin
# 2. 重启
dsh web
# 3. 打开 设置 → 个性化皮肤 → 主题皮肤，挑一套 → 完。
```

> 装的是 npm 已完成发布的正式包，无需 clone。若 `dsh plugin add` 报 workspace 相关错误，补一个 `-w` 即可。
> 两种情况下请把版本号写死（`npm view dsh-dream-skin version` 当场查号）：**刚发版的 24 小时内**（pnpm 冷静期会静默装上旧版），
> 以及**从 9.x 升上来的老 profile**（`^9.29.0` 覆盖不到 10.x）——见下文「安装」与「更新」。

## 📦 安装

四种方式任选其一，装完**重启 DSH Web** 即生效（当前会话会中断，但 DSH 会话有磁盘持久化，重启后可以恢复）。

### 方式一：npm 正式包（**推荐**，最简单）

```sh
dsh plugin --profile web add dsh-dream-skin
```

> **刚发版的那 24 小时内，请把版本号写死**：`dsh plugin --profile web add dsh-dream-skin@<最新版本>`（版本号当场查：`npm view dsh-dream-skin version`）。
> 原因是 pnpm 的 `minimumReleaseAge`（新版本冷静期）会把不带版本号的 `add`/`update` **静默解析成上一个"成熟"版本**，
> 并在输出里只留一行提示（如 `+ dsh-dream-skin ^9.27.1` / `(9.29.0 is available)`）。若那个旧版本的主机 peer 范围
> 不覆盖你当前的 dsh 运行时（例如 9.27.x 声明 `^0.1.0-rc.6`，不含 0.2.x），宿主会在安装期直接拒绝并回滚
> `package.json` / `pnpm-lock.yaml` / `node_modules`，报错看起来像"插件不兼容"，实际是**没装上最新兼容版**。
> 显式写版本号会让 pnpm 自动把该版本加入 profile 的 `minimumReleaseAgeExclude`，不再退回旧版。
> 等冷静期过了（发布时刻 +24h）用不带版本号的命令效果相同。桌面版同理，把 `--profile web` 换成你实际的 profile 名
> （在 `%USERPROFILE%\.dsh\profiles\` 下看目录名）；**桌面 profile 由 Electron 应用独占管理，CLI 会硬拒**，
> 走 `docs/desktop-support.md` 里那条走得通的路。

### 方式二：从 GitCode 源码安装（固定到已验证的提交）

```sh
git clone https://gitcode.com/LLLAAAAA/dsh-dream-skin.git
cd dsh-dream-skin && git checkout <40位commit>
dsh plugin --profile web add .
```

> 先把本地工作树固定到 release 对应的 commit，再用本地 link 装入；`main` 上的新提交不会自己跑进这个目录（但它是 `link:` 安装，手动改本地文件会立即生效）。原 `github:` 简写随 GitHub 账号封禁已不可解析（`npm view` 回报 account suspended），不要再用。

### 方式三：从 Release tarball 安装（离线 / 不便走 git 的环境）

从本仓库 [npm](https://registry.npmjs.org/dsh-dream-skin/) 下载 `dsh-dream-skin-<版本>.tgz`（内含构建好的 `lib/client.js`，安装时无需执行任何 prepare 脚本），然后：

```sh
dsh plugin --profile web add ./dsh-dream-skin-<版本>.tgz
```

### 方式四：克隆后从本地路径安装（开发迭代）

```sh
git clone https://gitcode.com/LLLAAAAA/dsh-dream-skin.git
cd dsh-dream-skin
dsh plugin --profile web add .
```

> `dsh plugin` 会把相对路径锚定到你**运行命令的目录**，装的是指向克隆目录的 link 依赖：改完源码保存，重启 DSH 即生效，无需重新安装。

**重启并验证**：

```sh
dsh web
dsh --profile web --dump-config | grep -A2 dream-skin   # 应出现 dream-skin loader 条目
```

打开 **设置 → 个性化皮肤**：自 11.1.0 起这一节分成四个分区——**主题与配色**（皮肤、强调色）、**玻璃效果**（材质、各面透明度、低功耗）、**背景与壁纸**（背景形式、图片来源、轮播、填充与取景）、**导入与导出**（主题包）。

> `-w` 标志在裸 `add` 时必需：每个 profile 自带 `pnpm-workspace.yaml`，pnpm 会把它当作 workspace 根，裸加报错
> `ERR_PNPM_ADDING_TO_ROOT`。若已加过 `-w`，后续用现有 workspace 即无需重复。

## 🔄 更新 / 卸载

<details>
<summary>⌄ 展开本节</summary>

**更新到最新版**（装的是 npm 正式包时）：

```sh
dsh plugin --profile web update dsh-dream-skin
dsh web   # 重启生效
```

> **刚发版的那 24 小时内，请把版本号写死。** pnpm 的「新版本冷静期」（`minimumReleaseAge`，默认 24 小时）会把
> 不带版本号的 `add` / `update` **静默解析成上一个"成熟"版本**——不报错，只在输出里留一行
> `(x.y.z is available)` 提示。若那个旧版本的主机 peer 范围不覆盖你当前的 dsh 运行时，宿主会在安装期直接拒绝并
> 回滚 `package.json` / `pnpm-lock.yaml` / `node_modules`，**看起来像"插件不兼容"，实际是没装上新版**。改用：
>
> ```sh
> dsh plugin --profile web add dsh-dream-skin@<最新版本>   # 显式版本会让 pnpm 把它加进 profile 的 minimumReleaseAgeExclude
> ```
>
> 桌面版同理，把 `--profile web` 换成实际 profile 名（`%USERPROFILE%\.dsh\profiles\` 下的目录名）。
> 完整说明与对照实验见 `docs/desktop-support.md`「宿主 peer 兼容闸门」一节的补充更正（issue #62 是 GitHub 时期的编号，迁移后未在新主机重建）。

> **老 profile 请直接用带版本号的 `add`，别指望 `update`**：`update` 沿用 `package.json` 里**已有的依赖范围**，
> 而 9.x 时代写下的 `dsh-dream-skin: ^9.29.0` 按 semver 永远覆盖不到 10.x（caret 只在同一个主版本内浮动），
> 于是 `update` 报"已是最新"、界面却还是旧版。改写这条依赖要用：
>
> ```sh
> dsh plugin --profile web add dsh-dream-skin@<最新版本>   # npm view dsh-dream-skin version 当场查号
> ```
>
> 这不是新缺陷，是**旧修复没送达**——排查这类"我明明更新了却没变化"请先核对实装版本号，
> 步骤见 [docs/publishing-to-npm.md](https://gitcode.com/LLLAAAAA/dsh-dream-skin/blob/main/docs/publishing-to-npm.md) 第九节。

**卸载**：

```sh
dsh plugin --profile web remove dsh-dream-skin
dsh web   # 重启后恢复官方外观
```

---

</details>

## 🧩 兼容性

| 项 | 值 |
|------|-----|
| DeepSeek Harness (`dsh`) | **同一构建兼容三代宿主**：`0.1.0-rc.6` ~ `0.1.x`（稳定版）与 `0.2.0-rc.1` / `0.2.x`（peer 已放宽为 `>=0.1.0-rc.6 <0.3.0-0`，宿主换代由运行时能力探测兜底）。**宿主升级后皮肤消失但插件显示已装？** 多半是 peer 窗口把整包跳过了——应急出路：`dsh plugin allow-version dsh-dream-skin@<版本> <宿主运行时版本>`（**用户自担风险的显式覆盖**，不是推荐做法），详见 [docs/desktop-support.md](https://gitcode.com/LLLAAAAA/dsh-dream-skin/blob/main/docs/desktop-support.md) |
| Node.js | `>=18` |
| 浏览器 | 现代 Chromium / WebKit（依赖原生 CSS 变量与 `matchMedia`） |
| 桌面端 | **第三方 DSH Desktop 壳**：已适配并实机复核（issue #50/#51/#55）。**官方 DSH Desktop**：证据只支持"**预期可加载**"，不支持"已支持"——profile 目录与"壳能加载本插件"这两件事本机已实测（装进 `~/.dsh/profiles/desktop`，用户重启壳后加载，活页读到过我方材质表；路径与读数见 `docs/publishing-to-npm.md` 8.4 与 `docs/desktop-support.md`），但**跨重启的设置持久化本机从未验证**，故本文档**不给**可复制的桌面安装命令。<!-- desktop-claim: load-expected-unverified -->`--profile` 取值必须用宿主**自带**的模板名，照抄第三方文档会装进空壳 profile；判断依据见 **[docs/desktop-support.md](https://gitcode.com/LLLAAAAA/dsh-dream-skin/blob/main/docs/desktop-support.md)** |

> **兼容机制**：插件把全部平台 seed 放在受控 `try` 内按候选顺序探测，宿主全部换代时降级为哑模块并打 `console.warn`，不会拖垮 DSH Web（issue #43 已根治）。`0.2.0-rc.1` 起宿主按 peer 范围在 boot 阶段**整包跳过**不兼容插件，peer 窗口即本插件的对外兼容窗口，由回归门强制与 manifest 一致。**但宿主闸门只认 `@deepseek-ai/dsh` 前缀的 peer**：`@deepseek-ai/cordis` 与 `react` **不参与**宿主兼容判定（由包管理器的 semver 解析单独把关）。判定细节与两把尺的对照表见 `tests/package.host_compat.test.cjs` 与 [docs/desktop-support.md](https://gitcode.com/LLLAAAAA/dsh-dream-skin/blob/main/docs/desktop-support.md)。

> **第三方目录（DSH-Store）现状**：`AI-Scarlett/DSH-Store#1411` 曾把本插件标为 catalog blocked。其中「`lib/client.js` 超过其审核面单文件上限」一条，已由对方 2026-10-15 的追评收回，原文与正文 sha256 存档在 [`docs/evidence/dsh-store-1411-followup-2026-10-15.md`](./docs/evidence/dsh-store-1411-followup-2026-10-15.md)；其追评留下的「扫描器证明不了 `require` 的有限调用集」由 10.16.0 处理（全文见 [docs/release-notes.md](https://gitcode.com/LLLAAAAA/dsh-dream-skin/blob/main/docs/release-notes.md)）。**本仓库不承诺收录状态会变绿**——是否放行取决于对方的审查流程。

## 📜 最近做了什么

**版本 11.16.0（2026-11-16）**：**壁纸轮换「保存文件夹 → 立刻列目录」时序修复轮。** 上一版把它记作「满载偶发的竞态、非本版引入」，本轮把用例开头的 `sleep(60)` 换成 `sleep(0)`，空载单跑就确定性翻红（`expected 3 / actual 2`），证实它是真实的产品时序 bug、不是测试噪声：保存文件夹后 `fetchFolderList()` 会先调 `flushStateToHost()` 把新路径推给宿主，但那时开机探测还没落定，守卫 `if (!hostProbeSettled) return` 直接把这次推送**丢掉**，紧随的列目录于是读到宿主文件里的**上一个**文件夹（旧目录 2 张图）。修法与恢复出厂那轮的 B2 同族：新增 `hostProbeDone` promise + 幂等 `settleHostProbe()`，三个落定出口统一走它；`flushStateToHost()` 未落定时挂起等待、落定后亲自补推一次，同时取消落定出口排的重复 debounce；探测自带 4 秒上限所以等待有界。配套把 15 秒列目录超时的起表从推送之前移到 `fetch` 之前——原位置会让等待探测烧掉列目录自己的预算、甚至请求未发出就 abort，这是被 `host never answers` 用例逼出的产品侧计时语义修正。回归门 **783** 条（781 通过 / 2 具名环境跳过，0 失败），质量审计 **229/229**。安装用确切版本号：`dsh plugin --profile web add dsh-dream-skin@11.16.0`。

**版本 11.14.1（2026-11-14）**：**宿主 0.2.2-rc.3 适配轮，已发版。** 上一版只把「插件能在 rc.3 上挂载」证到了运行时层，整套门禁在 rc.3 上还有 28 条红灯；本版把 28 条逐条查清——**只有一条是宿主真的移除了东西**（会话列表末尾那条 `_fade` 在 rc.3 里已经不存在），其余都是**我方读取层被宿主的字符串字面量换代打瞎**：rc.3 把编译产物里的字符串从双引号改成反引号模板，只认双引号的读取器于是「读到零条宿主 CSS」，把还在的 token 报成「被移除」。修法不是放宽门，而是让读取器两种拼写都认，并把宿主真的撤掉的那一面按**退役**记账（处置 `host-retired` + 带两个 sha256 见证的 tarball 归档 `scripts/data/legacy-host-fade-css.json`，只在「新扫描证明宿主确实没有 `.<base>_fade{` 规则」时合法，宿主把面画回来当场翻红）。census 重测到 DSH **0.2.2-rc.3**（337 包 / 1526 文件 / 3055 token），前向 gap 17 → **34**：新增 17 枚里 2 枚 `derived`、15 枚 `not-skinned`，其中 11 枚是 macOS-only 的玻璃 / 水洗车道，本机 Windows 门测不到，按边界写明而不是假装覆盖。回归门 **782** 条（780 通过 / 2 具名环境跳过，0 失败），质量审计 **229/229**。安装用确切版本号：`dsh plugin --profile web add dsh-dream-skin@11.14.1`。

**版本 11.14.0（2026-11-14）**：**主阵地恢复轮，已发版。** GitHub 账号封禁、仓库迁到 GitCode 之后的第一版正式发布：合入社区 PR #1 / #2 的运行时修复，修掉 issue #1 / #2 / #3 描述的三处缺陷，把宿主 census 重测到 DSH **0.2.2-rc.1**，并完成蓝军 / 第三方 / 中立裁定的三方评审逐个销账。回归门 **782** 条（780 通过 / 2 具名环境跳过，0 失败）、质量审计 **229/229**（217 调色 + 12 工艺）。安装用确切版本号：`dsh plugin --profile web add dsh-dream-skin@11.14.0`。

> **本轮细节**：合入社区 PR #1 / #2、修掉 issue #1 / #2 / #3 描述的三处缺陷之后，`main` 的回归门从 776 涨到 **782** 条：776 → 779 是两个 PR 带来的计算样式与图标插槽用例，+1 是恢复 `tests/client.plugin_page.test.cjs` 里被 PR #1 顺手删掉的那条正向契约断言，+1 是三方评审 B-02 补上的「有图标插槽的宿主在 `apply()` 当场停用 legacy hook」集成用例（用例内嵌反向变异，删掉停用调用必须翻红），再 +1 是宿主漂移逼出来的「已退休宿主插槽」门禁。重测 census 到 0.2.2-rc.1 时，宿主把 `--dsw-specific-sidebar-nav-item-hover` 整个移出了 token 语料（旧 0.2.1-rc.5 census 实测 1 个消费者 / 2 处声明），八套皮肤却仍在发它；兼容矩阵还支持旧宿主，所以不能删，改为把旧读数钉到归档 census 的具体提交上、并让该类别的四条反向变异都可翻红（`scripts/data/retired-host-slots.json`）。同时把 `tests/wash.cascade.test.cjs` 中写死宿主字面量的变异锚点改成从夹具现场解析——宿主把 `--dsh-sidebar-inline-padding` 从 12px 改成 8px 之后，那条变异已经退化成空操作；`tests/package.links.test.cjs` 新纳入 `github:` shorthand 这条禁止形状，并把历史豁免改成「档案保留陈述、但不暴露可点击死链」的 fence 感知双向变异检查（CHANGELOG 的旧 release 链接已降级成无 scheme 的行内代码，Store 证据的原文块则一字节不动，由 sha256 见证守着）。首屏主预览图因 GitCode 按内容拒绝预览而撤下，八份 README 改为只展示可用的设置实机截图。质量审计 229/229（217 调色 + 12 工艺）不变。

**版本 11.7.0（2026-11-07）**：**这一版只改一件事：编号。** 迁移那一版发出去时已经是 2026-11-06 23:35（UTC+8，registry `time` 戳 `2026-11-06T15:35:49.955Z` 现读），而它带着 11-04 写好的候选号 **11.4.2**——本项目的版本是日期式的（`M.D.X`，日取发版当天），跨日就该整体改名再发，这一次是我发晚了，**规则被我破掉、不是我改过规则**。npm 不可变，11.4.2 永久留在 registry 上（`latest` 现在被 11.7.0 取代；我**不 deprecate** 它，因为代码是好的、只是编号错，deprecate 会让按 `latest` 装的人在提示窗口里读到一条警告，那条警告对他们是噪声）。**与 11.4.2 的真实差异**：`package.json` / `package-lock.json` 的版本号、`lib/client.js` 里 `PLUGIN_BUILD` 一枚等长字符串（文件 **616,207 B 不变**）、文档里的日期与编号陈述；运行时代码零变化。回归门 **776** 条（与 11.4.2 同一套，本版不加用例）、质量审计 **229/229**（217 调色 + 12 工艺）。发版用确切版本号：`dsh plugin --profile web add dsh-dream-skin@11.7.0`。

**版本 11.4.2（写于 2026-11-04，实际发布 2026-11-06 23:35 UTC+8 · 编号跨日，已在 11.7.0 说明）**：**主阵地迁移：GitHub 账号被封禁，仓库搬到 GitCode。** 原坐标 `github.com/RevolutionLA/dsh-dream-skin` 现在匿名实测是 **404**，所以 README / 七份译文 / `package.json` 的 `repository`·`bugs`·`homepage` / CONTRIBUTING / issue 模板 / 安装 skill / 发布手册里的仓库地址与预览图地址全部改为 GitCode（预览图走 `raw.gitcode.com/…/raw/main/docs/previews/<皮肤>.png`，`main` 推送之后现测 8 张 `200 image/png` 且与本机 `docs/previews` **逐字节相同 8/8**；推送后的头几分钟同一条 URL 会先回 302 占位图或 403「暂不支持预览」，那是传播与缓存、不是坏链接，`README.md` 与 `package.json` 同批由 403 转 200，观察与未查明之处写在 CHANGELOG 11.4.2 第五节）。**没有替换成我验证不了的地址**：GitCode 的 `releases` 页对假路径回同一份 5,792 字节 SPA 外壳，无法确认存在，因此离线安装的 tarball 改成指向 **npm registry**（实测 200；每一版发布后都把 registry 上的 tarball 与本机 `npm pack` 逐字节比对，11.4.1 那一次是 0 处不一致，11.4.2 的对照结果写在 CHANGELOG 11.4.2 第四节）；`adversarial-review` 那个新地址实测返回 JSON 404，所以只留名字不留链接。**CI 口径随之改变**：GitHub Actions 的四个 Node 矩阵、computed-style 门、typecheck、finite-caller-set、Plugin Security Scan 随账号停跑，GitCode 流水线**尚未接上**——发版前的门现在是本机命令（`npm test` / `npm run skin:check` / `npm run typecheck` / `node scripts/verify-finite-caller-set.cjs` / `npm pack` 对照），README 的 CI 徽章已摘，`docs/desktop-support.md` 两处"由 CI 强制"改成本机实测读数；CHANGELOG 里 11.4.1 及更早的"CI 全绿"是当时 GitHub Actions 的真实读数，**保留不改**（那是历史，不是现在的承诺）。新增一条会失败的门：`tests/package.links.test.cjs` 现在禁止**指引类文档**携带已死坐标或未验证地址（四条禁止形状各配一条注入腿，点名翻红）。历史豁免划的是**陈述**而不是**链接**：`CHANGELOG.md` 与 `docs/evidence/` 里当年的读数与原文是历史记录，改掉等于篡改（门反过来断言 CHANGELOG 仍带旧坐标——被悄悄改名就说明这条腿在守一间空屋子）；而 `docs/release-notes.md` 那句"全文见 CHANGELOG.md"是导航链接，已经重指，因此它进了受门集合，可它自己的 `610/610` 一个字没动。回归门 **776** 条（774→776，新门两条），质量审计 **229/229**（217 调色 + 12 工艺），`lib/client.js` **616,207 B**、天花板 608 KiB、余量 **6,385 B**。**待人工**：DSH Store / awesome-ai-plugins / HOL / DSH Insights 这四个收录渠道按 GitHub 坐标识别本项目，是否还有效**未验证**，需要在新主机上重新登记。**已知边界**：`docs/computed-style-gate-in-ci.md` 那条计算样式门今天确实只剩维护机在跑（`wash-gate` job 随账号停跑，文档顶部已注明）；`npm test` 满载时偶红的那条 folder-rotation 用例，机制本轮查明——宿主 map 未落定时保存文件夹，列表读的是**上一个**文件夹（把用例开头的 60 ms 换成 0 ms 在空载机器上确定性翻红），修法与恢复出厂那轮的 B2 同族，**作为独立一版发**、不混进迁移版，判别命令与证据在 CHANGELOG 11.4.2 第五节。发版用确切版本号：`dsh plugin --profile web add dsh-dream-skin@11.4.2`。

**版本 11.4.1（2026-11-04）**：**社区贡献 @Wildchiken（PR #135）——「玻璃效果」那一区长出一枚折叠，并删掉两枚假开关。** 「单独设置输入框透明度」「单独设置弹窗透明度」是组件内部的**视图状态**：什么都不存、刷新回到打开，作用只是卸载下面那根滑杆，所以整枚去掉；侧边栏 / 输入框 / 弹窗三根透明度滑杆收进一行默认收起的折叠（`<button aria-expanded>`，开合不存储），侧边栏那枚真有作用的"是否跟随壁纸"保留。**没有壁纸时只收起「壁纸能见度」**（它只作用在页面背后那一层，没图时拖了不变任何东西），**「壁纸模糊度」留在原位**——`applyMaterialBlur()` 从同一枚键派生全页玻璃表面的 `--dsh-dream-skin-glass-blur`，跟有没有壁纸无关，而这根滑杆是整页唯一把手。新用例钉的是不变式而不是排版：以清空壁纸的 profile 启动，断言通道仍在发布（`14px`）、整页 `background.blur` **恰好一处**可寻、拖到 30 变量真的变 `30px`——**收起一个控件，不许让一个仍然生效的通道失去最后一个控件**。回归门 **774** 条（本版 **+2**，全在 `tests/client.settings_ui.test.cjs`），质量审计 **229/229**（217 调色 + 12 工艺），合成器预算一项没涨。**我怎么核的**：把 `main` × PR 做成真实合并在合并态跑全套，774 / 768 通过 / 1 具名跳过，**5 条红全是机械项**（4 条文档计数、1 条体积天花板），恢复出厂那 25 条与 smoke 187 条行为面零冲突；被删的两枚词典键与两个 helper 全树**零孤儿引用**；仓库里没有任何文档在宣传被删的开关。**边界**：天花板 600 → **608 KiB**——合并后 `lib/client.js` **616,207 B** 超原档 1,821 B，**字节数不是硬条件，几 KB 不算什么**，该问的是改动让不让项目更好；这是维护者的决定，写在门注释里，瘦身的账仍挂着但不再是合并的前置条件。六语新措辞是机器辅助翻译，请母语者把关；折叠默认收起**不持久化**（每次重开要再点一次）；**没有活页目视**，视觉结论仍需要有真页面的人看。发版用确切版本号：`dsh plugin --profile web add dsh-dream-skin@11.4.1`。

**版本 11.4.0（2026-11-04）**：**设置页多一枚「恢复出厂设置」，重点全在作用域上。** 它把**设置**改回出厂值——滑杆、开关、皮肤、强调色、材质、壁纸数值与取景，**壁纸链接本身也回到出厂那张（必应每日）**；**导入的主题包、收藏、壁纸文件夹路径与轮播列表一律不动**（那是你带进来的内容，不是"默认"该覆盖的东西），低功耗回到「自动跟随系统」。做法是把本插件的 29 枚存储键分进四个桶（写回 / 删键 / 逐字段复位 / 不许动，每枚带理由），门从 bundle 文本现场枚举键名要求**恰好归一桶**——下一版加设置却不进桶，它会点名红。按下是两段式确认，标签自己就说明保留什么。回归门 **772** 条（740→772，+32，其中 10 条是变异用例、8 条在改过的 bundle 上实跑），质量审计 **229/229**（217 调色 + 12 工艺），合成器预算一项没涨。**发版前自己跟自己对打了两轮**：第一轮实测出「宿主答复还没到就按下复位」会把轮播的链接列表清成空并推回 `dream-skin.json`——正是这枚按钮唯一会吃掉你内容的形状。改成「看得见才写」之后，第二轮又抓出三个新形状：合并写会把超过 20 条的列表截成 20、`{}`/`null`/损坏值被当成空列表推回去、答复迟到时挂起的那一段会盖掉你按下之后又改的设置。现在写的是**从你文件里原样复制的 `urls`**（不重走过滤、不截断），读不出列表的一律不写也不推，挂起段只在你没有新动作时才补执行。**边界**：`lib/client.js` **614,386 B**、天花板 600 KiB（本轮为这枚按钮抬的档，数字与理由写在门注释里）、余量 **14 B**——档已经吃满，**下一轮再加东西以前必须先真瘦身**；**没有活页目视**——armed 标签变长后的窄屏排布只有渲染级证据；复位**不撤回**；宿主整场没答话时这一轮**不动轮播**（少做一项，而不是赌一次覆盖）。发版用确切版本号：`dsh plugin --profile web add dsh-dream-skin@11.4.0`。

| 版本 | 日期 | 一句话 |
|---|---|---|
| **11.16.0** | 2026-11-16 | 壁纸轮换时序修复：保存文件夹零等待也能让宿主列对新目录，挂起推送 + 幂等落定，回归门 783 条 |
| **11.14.1** | 2026-11-14 | 宿主 0.2.2-rc.3 适配轮：重测 census、修掉字面量换代打瞎的读取器、把已撤的 fade 面按退役记账，回归门重新全绿 |
| **11.14.0** | 2026-11-14 | GitCode 恢复轮：合入社区 PR、修 3 个 issue、三方评审销账、宿主 0.2.2-rc.1 重测，迁移死链全部收口 |
| **11.7.0** | 2026-11-07 | 只改编号：迁移那一版实际发布跨了两天，日期式版本号回到规则内 |
| **11.4.2** | 2026-11-06 | 主阵地搬到 GitCode（GitHub 账号被封）：地址与预览图全部重指，CI 口径改成本机实测，多一条会失败的死链门 |
| **11.4.1** | 2026-11-04 | 社区贡献 @Wildchiken（PR #135）：玻璃那一区删掉两枚假开关、三根透明度滑杆收进折叠，壁纸模糊度留在原位 |
| **11.4.0** | 2026-11-04 | 「恢复出厂设置」：改回所有设置项，但不碰你导入的东西 |
| **11.3.0** | 2026-11-03 | 宿主快照重取 0.2.1-rc.5，顺带修掉一条把每个宿主版本都读成"可装载"的发版闸门 |
| **11.2.0** | 2026-11-02 | 插件管理页按报告者的诊断重做（我上一版是错的）；轮播文件夹改走宿主自己的目录选择器 |
| **11.1.1** | 2026-11-01 | 「壁纸模糊度」在低功耗下不出效果？现在它会说出来 |

> 更完整的逐版本记录（含当时的实测读数、反向破坏验证与未验证边界）在 **[CHANGELOG.md](https://gitcode.com/LLLAAAAA/dsh-dream-skin/blob/main/CHANGELOG.md)**；11.3.0 一路回到 9.9.0 的归档在 **[docs/release-notes.md](https://gitcode.com/LLLAAAAA/dsh-dream-skin/blob/main/docs/release-notes.md)**。首页不留第二份历史。

---

## ⚙️ 工作原理

DSH 的主题系统是 token 化的：web 外壳内置 `--dsw-*` 设计令牌，`ThemeRuntime` 允许第三方插件注册主题去
覆盖别名层（`--dsw-alias-*`）。本插件是标准的「双面」插件：

```text
                ┌─────────────────────────────────────────────┐
                │            dsh-dream-skin (双面插件)          │
                ├────────────────────────────┬────────────────┤
    Host 半边   │  lib/index.js              │  浏览器半边      │
                │  cordis.patch.yml 插入      │  lib/client.js │
                │  dream-skin loader 入口     │  __ModuleLoader__│
                └────────────────────────────┴────────────────┘
                             │                         │
                        profile 树加载              /plugins/dsh-dream-skin/client.js
                                                         │
        ┌────────────────────────────────┬────────────────┐
        │                                │                │
   ctx.theme.register(8套皮肤)      ctx.theme.overrideTokens(壁纸半透明)   ctx.slots.inject('settings.section' + 'settings.dreamSkin.item')
```

- **Host 半边**（`lib/index.js`）：`dsh.bundle` patch 层，插入 `dream-skin` loader 入口；`apply` 为空操作，
  与官方 `ui-*` 包同构。
- **浏览器半边**（`lib/client.js`）：
  1. `ctx.theme.register(...)` 注册 8 套皮肤；
  2. 恢复上次保存的皮肤并 `ctx.theme.setTheme(...)` 应用；
  3. 壁纸渲染为 `z-index:-1` 固定背景层（「模糊填充」档在其后再插一层同图放大溢出层，靠 DOM
     树顺序而非 z-index 压在图片层之下），叠加 `ctx.theme.overrideTokens(...)` 让主画布
     （`--dsw-alias-bg-base`）与侧边栏（`--dsw-specific-sidebar-fill`）半透明；
  4. 监听 `theme/change`，切皮肤 / 深浅色时自动重新着色壁纸洗色层；
  5. 注册独立的 **设置 → 个性化皮肤** 分节（`settings.section`），7 个功能行挂在
     `settings.dreamSkin.item` 插槽下。

每套皮肤携带自己的 `colorScheme`（`light`/`dark`）；本插件把它打在自己的根元素 `<html>` 上
（`data-dsh-dream-skin-scheme`），**不**押宿主的 `body[data-ds-dark-theme]`——那个属性归 ui-layout 的
ThemePresenter 所有，宿主 `dispose()` 会把它擦掉，于是"属性缺席"的窗口里暗色皮肤会拿到亮档常量。
别名 token 覆盖作为 `<body>` 内联自定义属性由 ui-layout 的 ThemePresenter 应用。

## 💼 持久化说明

<details>
<summary>⌄ 展开本节</summary>

- **三层**：内存缓存（保证首帧正确）→ 浏览器 `localStorage`（键前缀 `dsh-dream-skin:`，同 origin 快速恢复）→
  **宿主文件** `$DSH_HOME/dream-skin.json`（经本插件自建的回环 `/dream-skin/api` 读写，见 `lib/index.js` 之
  `statePath()` / `readState()` / `writeState()`）。
- **为什么桌面端必须有第三层**：DSH Desktop 每次启动由 OS 分配端口 → 浏览器 origin 每次都变 → 只靠
  `localStorage` 会"失忆"。宿主文件层才是跨端口、跨重启的权威状态，所以**桌面版换端口或重启都不会丢皮肤与壁纸**。
- 为何不用 Host settings？DSH 的 Host settings 线路只向浏览器暴露一份白名单命名空间
  （`dsh-host-apiproxy` 的 `WEB_SETTINGS_NAMESPACES`），第三方命名空间会返回 `settings-not-exposed`；
  产品本身也把远程浏览器偏好进程化。上面那层宿主文件走的是**插件自己的回环 HTTP 接口**，不经过那条白名单，
  所以既拿到了文件持久化，也没有碰任何非官方通道。

---

</details>

## 🛠️ 开发 / 扩展主题

客户端 bundle 直接以 `__ModuleLoader__` 格式编写（即 tsdown 为官方 `ui-*` 包输出的形态），**免构建**。
`lib/client.js` 只能 `require` 模块表实体：平台种子词（`react`、`react/jsx-runtime`、…）与已注册客户端
bundle（`@deepseek-ai/dsh-client-runtime/client`、…）。

- **新增一套内置皮肤**：在 `lib/client.js` 的 `SKINS` 数组加一个对象（`id` + `colorScheme` + `tokens`），
  它即自动出现在设置里；记得在**全部 8 种语言词典**（`zh`/`en`/`ja`/`ko`/`es`/`fr`/`de`/`ru`）补 `skin.<id>` 文案。
- **做一个主题包（推荐分发方式）**：参考 [`docs/examples/sample-theme-pack.json`](./docs/examples/sample-theme-pack.json)，
  一个 `*.dsh-theme.json` 即可在设置里导入或通过分享链接分发给别人，无需改代码。
- **放你自己的壁纸**：把图片丢进 [`wallpapers/`](https://gitcode.com/LLLAAAAA/dsh-dream-skin/tree/main/wallpapers)（注意只在你有权限的前提下分发），再在
  DSH 的「背景图片」里导入即可。
- **更新预览图**：预览由 `scripts/generate-skin-mockups.cjs`（真实 token + 弥散光）生成 HTML mockup，
  用无头 Chrome 截图即得 `docs/previews/*.png`，改皮肤 token 后重跑即可保持预览与真实 skin 同步。`docs/previews/manifest.json` 把每张图钉在三重指纹上（发货 token、卡片版式、图片字节与像素尺寸），`npm run previews --check`（不需要浏览器）在「只改配色、没重照图」时翻红并点名是哪套皮肤；找不到无头浏览器时 `npm run previews` 非零退出，不再把 0 产出当成功。这些 PNG **不随包发布**：2.26 MB 的 README 装饰不该由每个使用者下载，`npm pack` 从 2.5 MB 降到 263 kB，README 里的预览图改指 GitHub 绝对地址。
- **跑校验**：`npm test`（VM 冒烟测试，覆盖 factory 求值、`apply` 挂载、主题包导入/持久化）。
- **换配色**：参考 `--dsw-alias-*` 令牌（完整契约见 [`docs/themes-spec.md`](./docs/themes-spec.md)）。

## 工程案例

- [拒绝测试全绿，为什么 `IMG_2340.JPG` 还是打不开？](https://gitcode.com/LLLAAAAA/dsh-dream-skin/blob/main/docs/case-study-listed-not-served.md)——从一次合并前拦截，看两个接口如何发生契约漂移，以及怎样用“列表中的每个名字都必须可服务”这条不变式防止复发。

## 📌 Roadmap

<details>
<summary>⌄ 展开本节</summary>

> **这张表只列未完成项。** 已交付能力见上文「功能一览」与 [CHANGELOG](https://gitcode.com/LLLAAAAA/dsh-dream-skin/blob/main/CHANGELOG.md)，不在两处留存量——双写必然漂移，本项目已经漂过一次。
> 每条必须带三样东西：**动机**（来自真实 issue 或实测数据，不写想象中的需求）、**规模**（S ≈ 一个晚上，M ≈ 一个功能版，L ≈ 需要先设计）、
> **验收判据**（一条**能失败**的检查，不是"做完就好"）。完成即从本表删除。「不做」区与待办同等重要——它替贡献者省掉白跑的一轮。

### A. 可靠性：宿主换代不再翻车

*动机：`0.2.0-rc.1` 实测 6 组宿主锚点漂 4 组——其中 3 组哈希确认换代（真漂移），1 组（含 `lXshSW_*`）宿主 CSS 仍在、只是面未挂载（10.5.0 起以 `notMounted` 与漂移分栏）；issue #62 用户侧表现为"皮肤一夜全消失"。*

- [ ] **M** 剩余装饰规则去哈希类名依赖（侧栏 / 文件面板改用自有 `data-dsh-dream-skin-*` 标记；composer 与 nav-icon 已证明这条路走得通）
      — 验收：**两道都过**——① 静态配对门 `tests/host.frosthooks.test.cjs` 为绿：每一条还押宿主构建哈希的规则，同一条选择器里必须带一个无哈希锚点，且该锚点要在两条渠道各自的发货字节里实测存在；② 运行时探针在 0.2.x 上给出 `drifted: [] && notMounted: [] && pending: false`。**10.13.0 把 `channelAbsent` 从判据里拿出来，只当事实读出**：一条每个缺席都能被「解释」满足的判据等于用散文当判据；换成静态门之后「把锚点摘掉」当场翻红，而哈希在某渠道缺席这件事仍然写在 `anchors` 里。**只读 `drifted` 一空仍不算达标**（10.8.0 的 `retired` 与 10.12.1 的 `channelAbsent` 都会把「已解释的缺席」移出 `drifted`）。判读口径见 `docs/desktop-support.md` 的「消费判读」
- [ ] **M** peer 窗口滚动到 `0.3.x` —— **阻塞在上游，不在我方**：截至 2026-10-10，registry 上 `@deepseek-ai/dsh` 的 `latest` 是 `0.2.0-rc.2`、版本列表止于 `0.2.1-alpha.2`，`0.3.x` 从未发布过（`npm view @deepseek-ai/dsh versions --json`）。没有可对齐的目标版本，这条既无法开工也无法验证；上文兼容性表里那条现行 peer 窗口已覆盖宿主至今发布过的**每一个**版本。
      — 验收：宿主真的放出 0.3.x 之后，先跑 `npm run host:preflight -- --profile-load`（那张兼容判定表与那次真实 profile 载入，如今正是这条命令的两半），通过才放宽；不放开就在文档写明"不支持"，绝不留静默跳过
- [ ] **S** 漂移探针盖不到「按需挂载」的功能面：提问卡 / 授权卡只在对话真的发起提问时才进 DOM，启动期的梯度采样必然把它们恒报为漂移，所以 10.5.0 有意把它们留在探针之外
      — 验收：一次真实提问后，`anchors` 能报出这两组功能锚点的命中 / 漏中，而刚打开的页面仍是 `drifted: []`

### B. 发布与安装通道

*动机：2026-09-29 官方桌面版 `0.2.0-rc.2` 上安装被拒；而维护机器是 `link:` 工作区安装——**这类问题在 link 安装下永远看不见**。*

- [ ] **M** 内网 / 离线分发路径文档化（Release tarball 机制已有，缺可照抄的步骤）｜PR-welcome

### C. 桌面版运维面

*动机：官方 Desktop 发布后开始出现"一个人管一批机器"的用户。这个画像目前真实接触点还少，所以先做便宜的两条，不一次铺满。*

- [ ] **M** 批量部署指南（profile 目录布局、`link:` 与 registry 安装的差别、`compatibility.json` 豁免键语义、动态端口）

### D. 产品体验

*动机：用户第一眼看得见的东西。但这两天收到的真实反馈（#61 / #62）全是可靠性而非体验问题，所以整组排在 A、B 之后。*

- [ ] **M** 首帧无闪烁（FOUC）：**先测**"首帧 → `apply()` 完成"的实际时间窗再决定做法，不测不动手
- [ ] **M** 社区主题库 —— **先定治理规则再写代码**。已核实主题包载荷不含任何图片字段（只有 token + 强调色 + 元信息），所以投稿天然不带图像版权风险，成本全在审核负担｜PR-welcome

### E. 不做 / 只接受 PR

- **在线色板 / 主题预览 Studio**：那是独立站点，不是插件能力，且与「社区主题库」作用重叠、更贵。
- **配置预置 / 策略下发**（管理员放一套默认皮肤，首启即生效；原 C 组占位，2026-10-10 判定后移入本节）：这条要动的是持久化的**写入优先级**——出厂种子现在必须让位于用户的 durable 文件（10.6.1 的 B1 门就是钉这个的），再加一层"管理员默认值"等于在一个刚被测试锁死的三态里塞第四个来源。而"一个人管一批机器"的画像目前还没有真实接触点，先不做；出现批量用户再重开。
- **任何注入式改宿主安装包 / 二进制的做法**：与"只走官方扩展点"的定位直接冲突，**永远不做**。

---

</details>

## 🤝 贡献

欢迎提交 Issue 与 PR！请先阅读 [贡献指南](https://gitcode.com/LLLAAAAA/dsh-dream-skin/blob/main/CONTRIBUTING.md)，并遵循 [Code of Conduct](https://gitcode.com/LLLAAAAA/dsh-dream-skin/blob/main/CODE_OF_CONDUCT.md)。

## ⭐ 支持这个项目

喜欢的话，给仓库点个 **Star ⭐**、在 npm 上点个 **👍**，或把它转发给你的 DSH 朋友——这会让更多人发现它，
也能激励持续维护。想一起做主题库 / 在线 Studio / 更多主题？欢迎来贡献。

## 🔒 安全

发现安全问题？请勿直接开公开 Issue——参见 [安全策略](https://gitcode.com/LLLAAAAA/dsh-dream-skin/blob/main/SECURITY.md)。

## 📄 开源协议

[MIT](./LICENSE)

## 🙏 致谢

<details>
<summary>⌄ 展开本节</summary>

- 架构与 API 参考：DeepSeek Harness 官方
  [ui-theme](https://github.com/deepseek-ai/deepseek-harness/tree/master/packages/client/ui-theme) 客户端包。
- 概念致敬：[Codex-Dream-Skin](https://github.com/Fei-Away/Codex-Dream-Skin)。

---

</details>

## 🧰 同作者的其他项目

<details>
<summary>⌄ 展开本节</summary>

- **adversarial-review** —— 三方对抗式代码评审 Agent Skill。蓝军（敌意审查）→ 第三方（独立审计）→ 中立裁定，给 AI coding agent 的结构化对抗评审闭环。**写插件、发版前把关时特别有用。**
- **[AscendMate](https://gitcode.com/LLLAAAAA/AscendMate)** —— 昇腾智算服务器的环境搭建、模型微调、推理部署、算子开发手册。
- **[ascend-assistant](https://gitcode.com/LLLAAAAA/ascend-assistant)** —— 昇腾服务器助手 Agent Skill，与 AscendMate 深度联动。

---

</details>

## 📈 成长曲线

> 双轴：左轴 **Star**，右轴 **累计下载量**。下载量来自 npm 官方 API，**跨平台连续、一天没断**；Star 因 2026-11 的主阵地迁移断成两段账，**两段不可拼接**。

<p align="center">
  <img src="https://raw.gitcode.com/LLLAAAAA/dsh-dream-skin/raw/main/docs/stats.png?v=4" alt="dsh-dream-skin 累计下载量与 Star 成长曲线：GitHub 段封存于 2026-11-02，GitCode 段自 11-10 重新计数" width="900"/>
</p>

* **累计下载量（青色，连续）**：从 2026-08-15 一路到今天，**结算至 2026-11-13 共 119,784 次**。npm 不认 GitHub 账号，所以这段历史和未来的采集都没受影响——它是这张图里唯一跨平台完整的线。npm 结算有约 1 天延迟，图上「结算至」就是这条线的真实终点。
* **GitHub Star（紫色，已封存）**：从 8-15 的 6 枚涨到 **11-02 的 301 枚**。账号封禁后该接口实测 404，这段数据冻结在 `docs/stats-history-github.json`，采集脚本**只读、不得改写**，时间也不会再往前走。
* **中间那道灰带（11-03 ~ 11-09）**：平台迁移期。没有数据就是没有数据——**不补 0、不连线**。把 301 直接连到 1 会画出一条根本不存在的断崖。
* **GitCode Star（亮紫，重新计数）**：从 11-10 的第一枚 star 起算，新主机从 1 开始。它和 301 差两个数量级，画在同一根轴上只有 2 像素高，所以在右下角单独开了一张**放大卡片**。
* **数据怎么来的**：`node scripts/collect-stats.mjs` 拉 npm 按天增量 + GitCode 的 `stargazers`（带 `starred_at`，逐日累计算法与 GitHub 那套一致），`node scripts/render-stats-svg.mjs` 出 SVG，`scripts/chart/svg-to-png.mjs` 转 PNG。GitHub Actions 随账号停跑后，采集改由**本机每周一定时任务**驱动；本机那周没开，图就停在原地，靠「结算至」「生成于」两个日期兜底，不会假装实时。


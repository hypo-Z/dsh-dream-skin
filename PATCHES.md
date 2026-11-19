# 本地改动记录

这个目录是 `dsh-dream-skin` 的本地 fork（基于 9.29.0 编译产物），通过 `link:` 安装到 DSH profile。

## 改了哪里

全部在 `lib/client.js`：

1. ~~NAV_CSS 块~~：导航网格已由 `dsh-nav-grid` 插件负责，本 fork 不再重复注入（11.16.0 升级时删除）。
2. **文件末尾追加 `dsh-pet-link` 段**：监听阅读器（`lamp-reader`）出现和输入框打字，调用 dsh-pet 的 `/anim`、`/broadcast` 让宠物联动。
   - 音乐联动不在这里，在 `~/code/dsh-music-panel` 的 `src/50-player.js`（`notifyPetMusic`）。
3. **文件末尾追加 `dsh-nav-drag` 段**：侧栏按钮拖动交换顺序，顺序存 localStorage（`dsh_nav_order`）。

## 同步上游新版

1. `npm pack dsh-dream-skin@<新版本>` 并解压
2. `git diff` 看新版相对本 fork 基线（`git log` 的 baseline 提交）改了什么
3. 把上面三段补丁重新贴到新 `lib/client.js`
4. 提交并重启 DSH

## 注意

- DSH 的客户端 bundle 在宿主启动时读取，改完必须**完整重启**，`Cmd+R` 不生效
- 不要在插件管理页对本插件点“更新/重装”，会把 `link:` 换回 npm 版本

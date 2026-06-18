# CSE5250 — Lecture 1 交互动画 (GitHub Pages)

这个仓库托管 Lecture 1 的三个交互式并行计算动画，通过 GitHub Pages 在线发布。

- `index.html` — 三个交互动画（完全自包含，0 个外部依赖）。GitHub Pages 默认加载这个文件。锚点切换已内置：`#demo1` / `#demo2` / `#demo3` 可直接跳到对应的 Demo。
- `.nojekyll` — 空文件，告诉 GitHub Pages 跳过 Jekyll 处理（可选，有备无患）。
- `Lecture1_Demos.html` / `demo1-3.html` — 原始文件（保留备份）。

## 一步步部署（全程不用命令行）

> 仓库已经建好（`xiangyucs/cse5250`），`index.html` 也已上传，所以只需要开启 GitHub Pages。

1. 打开仓库页面，点顶部的 **Settings**（设置）。
2. 在左侧菜单里点 **Pages**。
3. 在 **Build and deployment → Source** 下拉里选 **Deploy from a branch**（从分支部署）。
4. 下面出现两个下拉框：
   - 第一个分支选 **main**
   - 第二个文件夹选 **/ (root)**
5. 点 **Save**（保存）。
6. 等约 1 分钟，刷新这个 Pages 设置页，顶部会出现绿色横幅显示你的网址，形如：

   ```
   https://xiangyucs.github.io/cse5250/
   ```

## 测试

- 打开 `https://xiangyucs.github.io/cse5250/` —— 应看到 **Demo 1**。
- 网址后加 `#demo2`，即 `https://xiangyucs.github.io/cse5250/#demo2` —— 应直接跳到 **Demo 2**。
- 同理 `#demo3` 跳到 **Demo 3**。

## 以后想更新动画？

直接在网页上 **编辑 `index.html`** 并提交即可；约 1 分钟后刷新网址就能看到新版本。

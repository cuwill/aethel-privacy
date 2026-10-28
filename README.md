# 隐私政策页（GitHub Pages）

这个文件夹里的 `index.html` 就是要发布的隐私政策页，单文件、无外部依赖。

发布步骤（不需要装 git，网页就能传）：

1. GitHub 上新建公开仓库 `aethel-privacy`（owner：cuwill）。
2. 仓库页 → Add file → Upload files → 把这个 `index.html` 拖进去 → Commit。
3. 仓库 Settings → Pages → Source 选 `Deploy from a branch`，
   Branch 选 `main` / `/ (root)` → Save。
4. 一两分钟后访问 `https://cuwill.github.io/aethel-privacy/`，
   把网址填到 App Store Connect 的「隐私政策网址」和「支持网址」。
5. 回到 App Store Connect → App 信息 → 隐私政策网址，
   同时把网址发回对话里，我核对页面显示。

`docs/privacy-policy.html` 是源文件；改内容时两边一起改，或者直接改这里再同步。

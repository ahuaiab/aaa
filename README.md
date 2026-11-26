# aaa — 站点（仅用于 Google OAuth 同意屏幕）

这个仓库只放两个静态页面，供 Google Auth Platform 的 Branding 页填写。**不含任何凭据。**

| 页面 | 用途 | 对应字段 |
| --- | --- | --- |
| `index.html` | 应用主页 | Application home page |
| `privacy.html` | 隐私政策 | Application privacy policy link |

线上地址：

- https://ahuaiab.github.io/aaa/
- https://ahuaiab.github.io/aaa/privacy.html

## 为什么必须是 public

GitHub 免费账号只能在 **公开仓库** 上启用 Pages。私有仓库会导致站点下线、上述 URL 404，Google 那边登记的链接随即失效。

仓库因此只保留这两个页面和一个 `.nojekyll`，历史也已重写为只含这些文件——早前误入的 `rclone.conf`（内含 OAuth token）不在任何公开历史中。

## 搬运任务在哪

见私有仓库 **ahuaiab/aba**：rclone 配置、workflow、文件清单都在那边。

## 更新方式

改文件后 push 到 `main`，Pages 1–2 分钟自动重建。
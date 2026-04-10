# Infans Games · GitHub Pages

本仓库为 **Infans Games**（上海未孩数字科技有限公司 / Shanghai Infans Digital Technology Co., Ltd.）官方网站静态站点，用于 GitHub Pages 部署。

线上地址（推送并开启 Pages 后）：<https://capoofun.github.io>

## 目录结构

| 路径 | 说明 |
| --- | --- |
| `index.html` | 首页（公司与产品展示） |
| `privacy.html` | 隐私政策 |
| `support.html` | 支持与联系 |
| `css/style.css` | 全站样式 |
| `images/` | 官网展示用截图与素材 |

## 本地预览

在项目根目录执行：

```bash
python3 -m http.server 8080
```

浏览器访问 `http://127.0.0.1:8080`（直接双击打开 `index.html` 也可预览，但建议使用本地服务器以验证相对路径）。

## 部署到 GitHub Pages

1. 在 GitHub 上创建 **Public** 仓库，仓库名必须为 **`capoofun.github.io`**（与用户名 `capoofun` 对应）。
2. 将本仓库推送到默认分支（通常为 `main`）。
3. 在仓库 **Settings → Pages** 中，Source 选择 **Deploy from a branch**，分支选 `main`，文件夹选 **`/ (root)`**。
4. 等待构建完成后访问 <https://capoofun.github.io>。

联系邮箱与政策正文以站内页面为准，请勿在仓库说明中写入未在官网公开的敏感信息。

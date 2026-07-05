# 一盏塔罗 · 抽一张牌

静下心,抽一张塔罗牌。每日一牌 + 三牌占卜(过去/现在/未来),即抽即解。

## 部署(GitHub Pages)

1. 新建 GitHub 仓库,把本目录全部文件(`index.html` + `cards/`)上传到仓库根目录
2. 仓库 Settings → Pages → Source 选择 `main` 分支根目录 → Save
3. 几分钟后访问 `https://<你的用户名>.github.io/<仓库名>/`

国内访问建议:将同一仓库接入 Cloudflare Pages 自动部署,或备案后迁移至国内静态托管。

## 目录结构

- `index.html` — 全部应用逻辑(单文件,零依赖)
- `cards/` — 78 张韦特塔罗牌面,WebP 格式(约 4.4MB,按需加载,每次占卜实际加载 1~3 张)

## 牌面图片来源

Rider–Waite–Smith 塔罗牌,1909 年初版,已进入公有领域(public domain)。
图片缺失时应用会自动回退到内置的极简金线牌面。

## 声明

本项目内容仅供娱乐与自我探索参考。

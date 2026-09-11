# Tidewatch · 潮观（公开展览）

加密 × 传统市场的**状态翻译**公开页（周报 / 看板 / 每日 / 日历）。

- **不是**交易建议，不喊单
- **无潮记 / 无问答 / 无收成哨**（那些只在作者本机）
- 数据来自作者本机厨房定时生成后导出；页内以「数据截至」为准
- 后期可迁公司 AWS；当前店面 = **GitHub Pages**

## 打开

部署启用 Pages 后：

- 首页：`https://terazhou.github.io/tidewatch-public/`
- 集锦：`…/site/`
- 看板：`…/site/dashboard.html`
- 每日：`…/site/daily.html`

本地预览：

```bash
python3 -m http.server 8767 --bind 127.0.0.1 --directory .
open http://127.0.0.1:8767/site/
```

## 来源

由 [Tidewatch](https://github.com/TeraZhou) 本机 `public-export` 生成（G1-1/G1-2）。勿提交密钥。

# Yanan — Portfolio

本地直接双击 `portfolio.html` 即可预览整站。

## 页面结构(均在根目录)
- `portfolio.html` — 首页（Hero + 2×2 项目网格 + About）
- `fatetell.html` — FateTell 案例
- `pagepop.html` — PagePop 案例
- `tennis.html` — Bouncie 案例
- `zeitro.html` — Zeitro 案例
- `tab.png` — 浏览器标签页图标（favicon，32×32）

## 资源目录(`assets/`，按项目分类)
```
assets/
├── home/        首页四张封面 dog-*.png
├── fatetell/    ft-*.png / ft-jiaobei.mp4 / IMG_3148-3150
├── pagepop/     pp-screens.png / pp-lamp-off.svg / pp-lamp-on.png
├── bouncie/     bouncie-*.png / bouncie-physics.mp4
├── zeitro/      zeitro-website.png / zeitro-annotated.png
└── _unsorted/   image 5.png（暂未使用，确认无用可删）
```

> 在 HTML 里引用图片时记得带相对路径，例如 `assets/home/dog-fatetell.png`。
> 当前页面未引用的素材：`fatetell/` 里的 `IMG_3148.PNG`、`IMG_3150.PNG`、`ft-tiger.png`、`ft-hexagram-dog.png`（保留备用）。

## 上线注意
- 文件名大小写：服务器通常区分大小写，改图后保持与 HTML 引用完全一致（已统一 `bouncie-physics.mp4` 为小写）。
- 部署到域名根目录后，可把首页 nav 的 `href="portfolio.html"` 改回 `href="/"`。

## 待办
- [x] 四张狗狗封面已就位
- [x] 社媒链接已设为 `x.com/YahahaFound`，已移除 Instagram
- [x] favicon 已设为 `tab.png`
- [x] 邮箱已设为 `guyananego@gmail.com`

# 天气图标 v2 源文件

这些 SVG 固定来自 `@meteocons/svg-static@0.1.0` 的 `flat` 目录。

本仓库只做以下处理：

- 删除部分图标右下角的叠加警告徽标；
- 对 `fire-alert` 解开原始遮罩，使火焰主体完整显示；
- 将颜色替换为 Bark 小尺寸通知中更清晰的统一色板；
- 转换为透明 PNG，并将主体最长边统一为 420/512。

`avalanche-danger-alert` 和 `falling-rocks-alert` 的三角形是原图主体，不是右下角叠加徽标，因此保留。

上游项目：<https://github.com/basmilius/meteocons>

上游许可证：同目录的 `LICENSE` 文件（MIT）。

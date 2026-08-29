# Bark Icons

用于个人 Bark 通知的公开静态图标仓库。仓库仅包含图片与开源来源说明，不包含任何 OpenWrt 配置、网络地址、程序、密码或密钥。

## 文件

- `icons/machine-status-v1.png`：机器状态
- `icons/machine-failure-v1.png`：机器故障
- `icons/machine-recovery-v1.png`：故障恢复
- `icons/machine-status-v2.png`：无右下角徽标的机器状态
- `icons/machine-failure-v2.png`：无右下角徽标的机器故障
- `icons/machine-recovery-v2.png`：无右下角徽标的故障恢复
- `icons/gold-ingot-v1.png`：黄金
- `icons/weather-*-v1.png`：天气与天气预警
- `source/*.svg`：机器图标的可审计矢量源文件
- `source/weather-flat-v2/*.svg`：天气 v2 的可审计矢量源文件

PNG 文件为 `512 × 512`、sRGB、透明画布。Telegram 和 Bitcoin 等圆形图标保留满幅圆形；黄金和天气图标裁掉原始透明留白后，将最长边统一为 420 像素（约 82%），并居中保留安全边距。天气 v2 去除了右下角叠加警告徽标，文件名带版本号以避开 Bark 的图标缓存。

## 来源与许可

服务器机架图形修改自 [Solar Icon Set](https://github.com/480-Design/Solar-Icon-Set) 的 `server-square-bold-duotone`，作者为 480 Design，依据 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) 使用。

本仓库对原图形进行了配色和圆形背景处理。v1 另外包含状态徽标；v2 移除右下角徽标，避免与 Bark 通知自身的角标区域重叠。衍生图标继续以 CC BY 4.0 提供。

黄金图标修改自 [Gold ingot icon.svg](https://commons.wikimedia.org/wiki/File:Gold_ingot_icon.svg)，作者为 Martin Strachoň，依据 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) 使用。

天气 v1 图标来自 [Meteocons](https://github.com/basmilius/meteocons) 的 `@meteocons/svg-static` Fill `0.1.0`，天气 v2 图标来自同一包的 Flat 目录，均依据 [MIT License](https://github.com/basmilius/meteocons/blob/main/LICENSE) 使用。v2 只进行去除叠加徽标、统一配色、PNG 转换、裁边、缩放和居中。

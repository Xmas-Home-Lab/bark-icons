# Bark Icons

用于个人 Bark 通知的公开静态图标仓库。仓库仅包含图片与开源来源说明，不包含任何 OpenWrt 配置、网络地址、程序、密码或密钥。

## 文件

- `icons/machine-status-v1.png`：机器状态
- `icons/machine-failure-v1.png`：机器故障
- `icons/machine-recovery-v1.png`：故障恢复
- `source/*.svg`：对应的可审计矢量源文件

PNG 文件为 `512 × 512`、sRGB、透明画布，针对 iOS 圆形通知头像保留了安全边距。文件名带版本号，因为 Bark 会永久缓存相同 URL 的图标。

## 来源与许可

服务器机架图形修改自 [Solar Icon Set](https://github.com/480-Design/Solar-Icon-Set) 的 `server-square-bold-duotone`，作者为 480 Design，依据 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) 使用。

本仓库对原图形进行了配色、圆形背景和状态徽标组合。衍生图标继续以 CC BY 4.0 提供。

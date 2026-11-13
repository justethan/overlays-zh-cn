# Overlays 简体中文（用户授权汉化版）

基于 [IterioDev/car-apps](https://github.com/IterioDev/car-apps) 的 Overlays **1.4.0**，将应用内设置页和介绍翻译为简体中文，发布为 **1.4.2（中文本地版本号，不是作者官方更新）**。1.4.1 因 macOS 扩展属性导致车机解包失败，请勿使用。。原作者：IterioDev；底层渲染及部分代码依赖原项目注明的作者。此仓库不是官方发布，不代表 IterioDev 背书。

原版许可和署名见 [IterioDev/car-apps/LICENSE.md](https://github.com/IterioDev/car-apps/blob/main/LICENSE.md)。仓库所有者表示已获得原作者对公开发布这个汉化版本的许可；**这不意味着其他人自动获得修改或再分发原项目的许可**。

应用 `iteriodev_overlays` 1.4.1 需要独立的 `iteriodev-overlays` 工具 0.5.0 和 `mgu-deploy` 0.7.5；这两个依赖**未在此仓库修改或打包**。车机限定 iDrive 8。

## 安装说明

1.4.2 已离线确认安装包不含扩展属性，实车安装仍待验证。

商店：Settings → Add source → `justethan/overlays-zh-cn` → Releases。联网后 Settings → Check now。若原版来自 IterioDev 来源，Store 对跨来源更新可能显示 blocked；**不能保证直接点击 Update**，不要卸载原版或重启车机来碰运气。先确认车机提供的来源切换/安装路径，或使用电脑通过官方 `mgu-deploy.sh check/install --artifact` 路径在已授权和备份后安装。

此包仅完成离线渲染、字形及目录校验，尚未在实车验证。先备份现有应用设置及软件状态；操作车辆需停稳、稳定供电。上游未来更新应用会覆盖中文，需要针对新版重新汉化。

## 下载

- [汉化源包（1.4.2）](https://github.com/justethan/overlays-zh-cn/releases/download/iteriodev_overlays%401.4.2/iteriodev_overlays%401.4.2.tgz)
- Store `catalog` 发布版提供在线目录。

# Hekate Toolbox 中文版

## 功能

- 读取和修改 hbmenu 启动按键组合
- 同时修改 hbmenu 配置，重启后设置依然生效
- 读取和修改 hbmenu 默认启动来源
- Sysmodule 热加载与卸载
- 重启到 Hekate 配置和 Hekate 菜单
- 启动到 UMS（SD 卡模式）
- Mariko 支持（功能受限）

## 编译

需要安装以下 devkitPro 包：

```
switch-libjpeg-turbo
switch-freetype
switch-dev
```

在项目根目录运行 `make` 命令，`out/` 目录将生成 `.nro` 文件。

## 许可

本项目基于 GPL-3.0 许可证开源，详情请参见 [LICENSE](LICENSE) 文件。

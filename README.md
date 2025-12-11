# MyChrome

## 概述

MyChrome 是一款用于 Google Chrome 的便携式启动器，可在无需安装的情况下部署和维护浏览器环境。借助 MyChrome，您可以灵活控制浏览器程序文件、用户数据以及缓存目录的位置，同时保持与官方版本一致的使用体验。

![https://github.com/user-attachments/assets/24b60d70-95ef-4e61-a8d4-d7dd1ca05844](https://github.com/user-attachments/assets/24b60d70-95ef-4e61-a8d4-d7dd1ca05844)

## 主要特性

- 自定义程序、数据与缓存目录，满足不同磁盘或权限策略。
- 一键构建 Chrome 便携版，可设置为系统默认浏览器。
- 支持 Stable / Beta / Dev / Canary / Chromium 多通道版本自动更新，允许配置代理并启用多线程下载以加速获取。
- 提供浏览器启动与退出钩子，可在关键节点调用外部脚本或工具。
- 内置多语言资源，便于创建和维护本地化界面。

## 下载与安装

1. 前往 [Release](./release) 页面获取最新的 `MyChrome.zip` 或 `MyChrome_x64.zip` 压缩包。
2. 解压至任意可读写目录，该目录将作为 `MyChrome` 和 `Google Chrome` 的工作根目录。
3. 运行 `MyChrome.exe` 打开配置界面，根据需要调整路径与更新策略。
4. 单击 `确定` 完成初始化设置。

> 如需重新进入配置界面，双击根目录中的 `MyChrome.vbs` 即可。

## 使用建议

- 将浏览器程序目录与数据目录放置在同一便携设备中，便于整体迁移。
- 针对多版本需求，可为不同渠道分别创建配置文件并独立维护。
- 若使用代理或镜像，请确保网络策略允许访问所需更新源。

## 多语言支持

项目默认提供简体中文、繁体中文与英语界面。如需新增语言，请按照以下流程操作：

1. 复制 `lang/en-US.ini` 或 `lang/zh-TW.ini` 作为模板。
2. 根据目标语言翻译各条目，保存为新的语言文件。
3. 在配置界面中选择新增语言即可生效。

## 更新与发布说明

- [更新日志](./CHANGELOG.md) 记录了每个版本的功能改进与修复。
- 新版本发布后，可在配置界面中选择自动更新或手动触发更新流程。

## 反馈与支持

- 通过 [Issues](./issues) 提交缺陷报告或功能建议。
- 提交反馈时，请附上使用的系统版本、MyChrome 版本以及相关日志，便于快速定位问题。

## License

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

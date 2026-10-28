# Embuary Flow 插件源

Kodi 21 使用的 Flow 皮肤、Helper 和安装助手。插件 ZIP 包含运行所需的 Python/XML 文件。

## 安装

1. 下载[仓库插件 ZIP](repository.embuary.flow/repository.embuary.flow-0.1.1.zip)，在 Kodi 选择「设置 → 插件 → 从 ZIP 文件安装」。
2. 选择「从仓库安装 → Embuary Flow → 程序插件 → Flow 安装助手」。
3. 打开安装助手，选择「准备安装包并打开原生安装 → 全部安装包」，按提示选择保存目录。
4. 在 Kodi 原生窗口逐个安装：四个配套补丁 → Flow Helper → Flow 皮肤。已匹配的包会跳过；版本或文件不匹配时先核对。
5. 在「界面 → 皮肤」选择 Flow，并在助手的「安装后的设置提示」中检查四个补丁插件的自动更新保护。缺少其他依赖时，使用助手的「安装缺少的仓库依赖」。

## 文件说明

- `repository.embuary.flow/`：仓库插件，用于添加本插件源。
- `script.embuary.flow.installer/`：安装助手，内含皮肤、Helper 和四个配套补丁包。
- `script.embuary.flow.helper/`：Flow 后台服务，提供导航和评分等功能。
- `skin.embuary.flow.probe/`：Flow 2K 皮肤及其图标、截图和背景图。
- `addons.xml`：仓库插件索引；`.sha256` 文件用于校验索引或对应 ZIP。

许可证：GPL-2.0-or-later；各内嵌插件保留自身许可证。

本项目使用 OpenAI Codex 辅助开发，部分代码由 Codex 参与编写与维护。

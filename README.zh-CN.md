# yanshi-extras · 偃师扩展仓

[English](README.md) | **简体中文**

偃师（Yanshi）主程序之外的扩展内容仓：demo 工程、模板工程、笔刷与纹理素材、预设与插件都放在这里，与主仓分开管理、分开授权。

主仓：[gradetwo/yanshi](https://github.com/gradetwo/yanshi) · 官网：<https://yanshi.wangda.today> · 在线试用：<https://yanshi-online.wangda.today>

Extras for the Yanshi painting engine — demo projects, template projects, brushes and textures, presets and plugins, kept separate from the main repository.

## 目录

| 目录 | 内容 |
|---|---|
| `demos/` | 可直接打开的 demo 工程。一个 demo 一个子目录，内含工程文件与说明（内容、所用素材与预设、许可）。 |
| `templates/` | 模板工程：画布尺寸、图层结构与常用设置预先搭好。一个模板一个子目录。 |
| `assets/` | 笔刷、纹理、纸面、样本图等素材。大文件走 Git LFS；每项素材注明来源与许可。 |
| `plugins/` | 偃师插件（介质、工具等）。一个插件一个子目录，自带说明与许可。 |
| `presets/` | 风格预设包。 |

## 使用

- demo 与模板工程：下载后用偃师打开即可。工程引用的素材若在本仓 `assets/` 下，按各工程说明里的相对路径放置。
- 素材：克隆本仓前先装 [Git LFS](https://git-lfs.com)（`git lfs install`），否则拉到的只是指针文件，不是素材本体。

## 许可

本仓内容按目录分别授权，以各子目录内的 `LICENSE` 或说明为准。

- `plugins/` 下的代码未单独注明时，与主仓一致（MIT）。
- 工程、素材、预设等内容未单独注明时，版权归各自作者所有；使用或再分发前先看对应目录的说明。

## 贡献

欢迎以 PR 形式添加内容。每个内容项自带一份简短说明：是什么、怎么用、来源与许可。

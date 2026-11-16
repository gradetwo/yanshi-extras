# yanshi-extras · Yanshi Extras

**English** | [简体中文](README.zh-CN.md)

Extras for the Yanshi painting engine, kept separate from the main repository and licensed separately: demo projects, template projects, brushes and textures, presets and plugins.

Main repository: [gradetwo/yanshi](https://github.com/gradetwo/yanshi) · Website: <https://yanshi.wangda.today> · Online demo: <https://yanshi-online.wangda.today>

## Contents

| Directory | Contents |
|---|---|
| `demos/` | Demo projects that open directly in Yanshi. One subdirectory per demo, containing the project files and a note (contents, assets and presets used, license). |
| `templates/` | Template projects: canvas size, layer structure and common settings set up in advance. One subdirectory per template. |
| `assets/` | Brushes, textures, paper surfaces, sample images and other assets. Large files are stored with Git LFS; every asset states its source and license. |
| `plugins/` | Yanshi plugins (media, tools, …). One subdirectory per plugin, with its own readme and license. |
| `presets/` | Style preset packs. |

## Usage

- Demo and template projects: download and open in Yanshi. If a project references assets from this repository's `assets/`, place them at the relative paths given in the project's note.
- Assets: install [Git LFS](https://git-lfs.com) (`git lfs install`) before cloning, otherwise you will only get pointer files instead of the actual assets.

## License

Content in this repository is licensed per directory; the `LICENSE` file or note inside each subdirectory governs.

- Code under `plugins/` is under the same license as the main repository (MIT) unless stated otherwise.
- Projects, assets, presets and other content remain the copyright of their respective authors unless stated otherwise; check the note in the corresponding directory before use or redistribution.

## Contributing

Contributions via pull request are welcome. Every item must carry a short note: what it is, how to use it, its source and its license.

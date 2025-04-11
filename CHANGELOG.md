# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed

- 修改标准色的定义：C：100，M：0，Y：100，K：60。
- 使用 illustrator 重新生成 logo 文件。
- 参考文献不显示 doi 和 url 。
- 修改模板性质。

### Added

- 重新支持 BibLaTeX 宏包。
- 添加 github CI。

## [v2.0.0-beta1] 2025-04-04

### Changed

- 数学式的改为段前6磅、段后6磅。
- 图表标题的对齐方式改为 `centerlast`（两端对齐、末行居中）。
- 删去 `sysusetup.tex` 中不必要的宏包。
- 修改 `sysuthesis.cls` 的 `sysuthesisversion` 。
- 修改 `README.md` ，对本模板的性质做了更准确的表述。

### Added

- 增加生僻字测试效果。
- 增加 `CHANGELOG.md` 文件。
- 可修改校徽等模板图片放置的文件夹，避免与正文内容的图片搞混。


[Unreleased]: https://github.com/1FCENdoge/SYSUThesis/compare/v2.0.0-beta1...HEAD
[v2.0.0-beta1]: https://github.com/1FCENdoge/SYSUThesis/compare/v2.0.0-alpha2...v2.0.0-beta1

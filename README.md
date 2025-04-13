# 中山大学毕业论文/设计 LaTeX 模板（本科/研究生）

[![GitHub release](https://img.shields.io/github/release/1FCENdoge/sysuthesis/all.svg)](https://github.com/1FCENdoge/sysuthesis/releases/latest)
[![GitHub commits](https://img.shields.io/github/commits-since/1FCENdoge/sysuthesis/latest.svg)](https://github.com/1FCENdoge/sysuthesis/commits/main/)
[![Build](https://github.com/1FCENdoge/sysuthesis/actions/workflows/main.yml/badge.svg)](https://github.com/1FCENdoge/sysuthesis/actions/workflows/main.yml)

本项目是中山大学的毕业论文/设计 LaTeX 模板 sysuthesis，基于中国科学技术大学学位论文LaTeX模板开发，兼容最新版的 TeX Live、MacTeX 、MiKTeX 发行版，支持跨平台使用。由于学校规定的研究生论文格式过于粗糙，部分格式参照中科大研究生论文格式进行设定，并且将本科和研究生的部分格式统一。

注意：

1. 使用说明文档 `sysuthesis-guide.pdf` 和模板预览文件 `main.pdf` 在发布版中附带，用户也可自行编译；**使用模板前应仔细阅读使用说明文档 `sysuthesis-guide.pdf`**。

2. 本科论文模板格式按照本科生论文规范编写，全校通用。研究生模板满足中法核工程与技术学院研究生论文格式要求的同时，
也为其他学院提供可供使用和参考的模板。

3. 本模板要求 TeX Live、MacTeX、MiKTeX 不低于 2017 年的发行版，
并且尽可能升级到最新。安装和升级方法见
[新手指南](https://github.com/ustctug/ustcthesis/wiki/新手指南)（借用中科大LaTeX模板的wiki页面）。

4. **不支持** [CTeX 套装](https://github.com/ustctug/ustcthesis/wiki/常见问题#3-模板支持用-ctex-套装编译吗)。


## 下载地址

- GitHub Releases：<https://github.com/1FCENdoge/sysuthesis/releases>

## 本地编译文档

- 编译模板的使用说明文档 `sysuthesis-guide.pdf`：
   ```
   latexmk -xelatex sysuthesis-guide.tex
   ```
- 编译论文 `main.pdf`：
   ```
   latexmk -xelatex main.tex
   ```
- 如需清理论文编译过程中的临时文件，可以：
   ```
   latexmk -c
   ```

- 以上编译过程也可以用 `make` 工具：
   ```
   make doc        # 编译生成 sysuthesis-guide.pdf
   make            # 编译生成论文 main.pdf
   make clean      # 删除编译过程中生成的临时文件
   ```

## overleaf 编辑（在线）

本模板可以使用 [overleaf](https://www.overleaf.com/) 在线编辑，需要在 [releases](https://github.com/1FCENdoge/sysuthesis/releases) 页面提前下载 `Source code (zip)`。

步骤如下：

1. 进入 [overleaf](https://overleaf.com) 并登录账号
2. 左侧 `New Project` 选择 `Upload Project`
3. 上传 `.zip` 压缩包，建立新项目
4. 点击 `menu`，滑动到下方 `Settings` 的 `Compiler` 选择 `XeLaTeX`
5. 打开 `main.tex` 文件，点击中间右侧上方的 `Recompile` 进行编译
6. 如果顺利可以看到 pdf 的预览
7. 如果无法加载图片只有路径信息，点击 `Recompile` 旁边的倒三角，其中的 `Compile Mode` 选择 `Normal` 模式

此时可以得到完整的 `main.pdf` 文件。

## 反馈问题

如果发现模板有问题，请按照以下步骤操作：

1. 阅读学校的标准，判断是否符合学校的要求：[本科生论文规范](https://lingnan.sysu.edu.cn/undergraduateprogram/node/753)；[研究生论文规范](https://graduate.sysu.edu.cn/sites/default/files/2019-04/中山大学研究生学位论文格式要求.pdf)；
2. 阅读 [常见问题 FAQ](https://github.com/ustctug/ustcthesis/wiki/常见问题)；
3. 将 TeX 发行版和宏包升级到最新，并且将模板升级到 Github 上最新版本，
查看问题是否已经修复；
4. 在 [GitHub Issues](https://github.com/ustctug/ustcthesis/issues)
中搜索该问题的关键词；
5. 在 [GitHub Issues](https://github.com/1FCENdoge/sysuthesis/issues)
中提出新 issue，并回答以下问题：
    - 使用了什么版本的 TeX Live / MacTeX / MiKTeX ？
    - 具体的问题是什么？
    - 正确的结果应该是什么样的？
    - 是否应该附上相关源码或者截图？

如果导师或者院系在格式上有额外的要求，请将老师的邮件转发给模板作者。
作者会考虑增加接口以便修改格式。


## 更多资料

- [本科生论文规范](https://lingnan.sysu.edu.cn/undergraduateprogram/node/753)
- [研究生论文规范](https://graduate.sysu.edu.cn/sites/default/files/2019-04/中山大学研究生学位论文格式要求.pdf)
- [LaTeX 新手入门指南](https://github.com/ustctug/ustcthesis/wiki/新手指南)
- [常见问题 FAQ](https://github.com/ustctug/ustcthesis/wiki/常见问题)
- [参与开发](https://github.com/ustctug/ustcthesis/wiki/参与开发)

# 共同维护约定

## 新增一项工作

1. 优先核实原始论文、官方项目页和代码仓库，避免同名工作混淆。
2. 复制 [笔记模板](templates/paper-note.md) 到 `notes/<work-name>.md`。
3. 在英文 [README](README.md) 和[中文 README](README.zh-CN.md) 的索引中同步增加工作及相关链接。

文件名使用小写英文及连字符；正文可以使用中文。每项工作维护一篇主笔记，多人直接补充同一文件。笔记按模板的 Background、Method、Experiments、Limitation 四部分展开。

## 内容与证据

- 引用实验数字时注明论文版本、图表编号或代码位置。
- 区分作者主张、定量验证、定性演示、自己的复现与推测。
- 项目 README 的性能描述按项目自报结果记录，不自动视为独立复现或同行评审结论。
- 无法核实的项目、链接和能力明确写“待核实”，不要根据名称推断。
- 论文优先保存官方链接；图片放入 `assets/<work-name>/`，并在笔记中注明出处。自制图表注明依据。
- 不上传模型权重、数据集、生成视频或临时输出等大文件。

## 提交与讨论

- 使用独立分支，例如 `notes/code-world-model`。
- 提交信息说明具体修改，例如 `docs: add Code World Model reading notes`。
- 通过 Pull Request 提交笔记，说明新增内容、证据来源和待讨论问题。
- 建议另一位成员审阅后合并；尚未达成共识的问题保留在笔记或 Issues 中。
- 两份 README 均仅保留项目索引和目录导航两个章节；主 README 使用英文。
- 项目索引统一使用 Work、Article、Website、Code、Notes 五列；使用 shields.io 徽章链接论文、网站、代码和笔记，尚未核实或缺失的链接用“—”表示。

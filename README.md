# Code World Model Reading

共同维护的 Code World Model 方向文档库，收录论文、开源项目、阅读笔记、横向比较与研究设想。

## 调研关注点

- **可执行世界状态**：状态如何表示、持久保存，并在动作与事件下更新？
- **代码与智能体**：Code / Agent 负责规则、动力学、规划还是环境构建？
- **视觉接口**：可执行状态通过何种中间表示连接到视频生成或渲染？
- **持续交互与控制**：是否支持流式生成、中途指令切换、相机控制及实时编辑？
- **验证与局限**：长期一致性、因果与规则遵循有哪些实验证据？

## 论文与项目索引

下表是初始收录清单。论文、开源实现和产品演示的性质以各自官方来源为准；缺失来源待核实后补充。

| 工作 | 论文 / 项目入口 | 阅读笔记 |
| --- | --- | --- |
| Programmable World Model | [arXiv](https://arxiv.org/abs/2609.10540) | [笔记](notes/programmable-world-model.md) |
| Code World Model | [arXiv](https://arxiv.org/abs/2608.25927) | [笔记](notes/code-world-model.md) |
| Streaming Code World Model | [GitHub](https://github.com/TingtingLiao/streaming-code-world-model) | [笔记](notes/streaming-code-world-model.md) |
| Code Video Model | 待补充官方链接 | [笔记](notes/code-video-model.md) |
| AgentGarten | 待补充官方链接 | [笔记](notes/agentgarten.md) |
| Edenlive | 待补充官方链接 | [笔记](notes/edenlive.md) |

> 笔记文件已建立阅读框架，尚未填入完整调研结论。

## 横向总结

- [方法比较](surveys/comparison.md)：状态表示、代码职责、视觉接口、交互能力与实验依据。
- [研究设想](surveys/research-ideas.md)：研究问题、实验假设、最小验证方案与评价标准。

## 目录导航

| 路径 | 用途 |
| --- | --- |
| [notes/](notes/) | 每项工作一篇阅读笔记 |
| [surveys/](surveys/) | 横向比较与研究设想 |
| [templates/paper-note.md](templates/paper-note.md) | 统一笔记模板 |
| [assets/](assets/) | 笔记图片与自制图表 |
| [CONTRIBUTING.md](CONTRIBUTING.md) | 共同维护约定 |

## 如何参与

1. 在 Issues 中提出收录建议、阅读问题或实验讨论，避免重复工作。
2. 复制笔记模板，在 `notes/` 下创建或补充对应 Markdown 文件。
3. 在新分支提交修改，并发起 Pull Request；建议由另一位成员核对方法理解和实验出处。
4. 合并后同步更新首页索引和相关横向总结。

论文原文优先链接官方来源。实验数值注明版本、图表与配置；区分作者结论、复现观察和阅读者推测。详细约定见 [CONTRIBUTING.md](CONTRIBUTING.md)。

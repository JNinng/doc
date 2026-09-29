# Skills

技能导航。每个技能一个目录，入口为 `SKILL.md`；复制到 `~/.agents/skills/<name>/` 即可被 agent 发现并按 description 自动触发。

| 技能 | 说明 |
| --- | --- |
| [doc-tidy](./doc-tidy/SKILL.md) | 文档清理（精简版）：审计并清理持久资产（ADR、README、CHANGELOG、代码注释）中的过程残留、生成痕迹与语言失配。面向能力较强的模型。 |
| [doc-tidy-full](./doc-tidy-full/SKILL.md) | 文档清理（细致版）：与 doc-tidy 同一规则集，展开术语定义、判别原则与工作流细节。面向能力较弱的模型。 |

> doc-tidy 与 doc-tidy-full 规则同步维护：迭代 doc-tidy 后同步更新 doc-tidy-full，保留其细致风格；两者只允许详略差异，不允许规则分叉。

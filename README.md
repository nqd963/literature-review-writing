<div align="center">

# 中国古代文学文献综述写作

**把「读过一堆论文」变成「对某一问题的研究史做出有根据的判断」**

[![文档站](https://img.shields.io/badge/文档站-GitHub%20Pages-8c3b32?style=flat-square)](https://nqd963.github.io/literature-review-writing/)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-通用%20SKILL.md-4a6b68?style=flat-square)](SKILL.md)
[![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](LICENSE)

[在线阅读 →](https://nqd963.github.io/literature-review-writing/) ｜ [领域地图](references/domain-ancient-literature.md) ｜ [范文解剖](references/worked-examples.md) ｜ [检查表](references/checklist-ancient-literature.md) ｜ [参考文献](REFERENCES.md)

</div>

---

## 这是什么

一套面向**中国古代文学**（先秦至近代，含诗、词、文、赋、小说、戏曲、文论）的文献综述写作方法论。

它采用 **Agent Skills 开放规范**（一个 `SKILL.md` + YAML frontmatter + 可选的 `references/`、`scripts/`），因此**不绑定任何特定产品**——任何实现了该规范的 harness（Claude Code、Codex CLI、WorkBuddy、Cursor 等）都能直接加载；不接 Agent 时，也可以当作一本独立手册阅读。

内容上，它保留了 Galvan & Galvan《Writing Literature Reviews》的四阶段骨架与综合纪律，但把**检索对象、证据标准、结构方式、引文体例全部换成了中国古代文学的领域规则**：

> **文献学与文艺学相结合。** 版本、校勘、系年、辨伪是地基；阐释、审美判断、文学史定位是建筑。没有地基的阐释站不住，没有阐释的考订不成文学研究。

---

## 与通用综述教程的六点不同

| | 通用（社科）教程 | 本指南 |
|---|---|---|
| 时效性 | 默认近 5 年 | 经典考证不可缺席，"新"不等于"重要" |
| 引文体例 | APA 作者—年份 | 页下脚注 + GB/T 7714—2025 |
| 证据基础 | 抽样、信效度、效应量 | 版本可靠性、材料真伪、论证链、学术史位置 |
| 古代材料 | 无对应 | **前研究史**：评点、序跋、诗话、选本须单列 |
| 考证 | 无对应 | 系年、版本、辑佚、辨伪是**固定栏目** |
| 统计 | 无要求 | 题目可穷尽，故**统计口径必须交代** |

---

## 四阶段工作流

```
① 检索管理          →   ② 分析文献          →   ③ 综合与初稿        →   ④ 编辑与终稿
主题·版本范围·双清单     笔记表·版本表·论点表     学术史地图·大纲·论证     脚注·核对·领域检查表
```

按顺序推进，允许回退。写作全程保持回到数据库和原典的开放心态。

<details>
<summary><b>核心心智（九条）</b></summary>

1. **综述不是成果清单，而是研究史判断。**
2. **证据有两层，不能混。** 原典是立论根据，研究文献是对话对象。
3. **文献学与文艺学相结合**（程千帆"两点论"）。
4. **辨章学术，考镜源流**（章学诚）——学术史综述的最高标准。
5. **版本意识是底线。** 古代文学没有"默认文本"。
6. **文史互证，但不机械比附。**
7. **综述者是裁判，不是速记员。**
8. **所有研究都有局限，永远不说"证明"。**
9. **目的决定写法**——课程论文 / 学位论文 / 开题报告 / 期刊论文 / 专题述评，五类要求完全不同。

</details>

---

## 目录

| 文件 | 内容 |
|---|---|
| [`SKILL.md`](SKILL.md) | 入口：心智模型、四阶段流程、红旗清单 18 条 |
| [`references/domain-ancient-literature.md`](references/domain-ancient-literature.md) | **领域地图**：四个特殊性、选题边界、时段/文体差异、五种结构范式、学术史写法 |
| [`references/worked-examples.md`](references/worked-examples.md) | **范文解剖**：陆游篇（通代）与贾谊篇（断代）逐节拆解、实操配方、十步 SOP |
| [`references/model-passage.md`](references/model-passage.md) | **示范段落**：一段可照着仿写的正文 + 逐句批注 + 反面对照（动笔前读） |
| [`references/search-resources.md`](references/search-resources.md) | 古籍库、研究库、资料汇编、海外汉学、关键词矩阵、引文追踪、检索日志 |
| [`references/academic-history-and-overseas.md`](references/academic-history-and-overseas.md) | 20 世纪以来四条脉络、港台/日本/欧美传统、核心争论 |
| [`references/editions-and-citations.md`](references/editions-and-citations.md) | 版本学、陈垣校法四例、辨伪辑佚、脚注规范、GB/T 7714—2025 |
| [`references/templates-domain.md`](references/templates-domain.md) | 笔记表、检索日志、版本谱系表、论点—证据表、大纲骨架、句式库 |
| [`references/checklist-ancient-literature.md`](references/checklist-ancient-literature.md) | 领域自检 60 项 + 硬伤 10 条 + 附录语言格式 20 条 + 最后三问 |
| `references/stage1-4*.md` | 通用层写作要点（据 Galvan 四阶段框架改写，已领域化；不含原书章节编号与逐条中译） |
| [`scripts/init_review_workspace.py`](scripts/init_review_workspace.py) | 一行命令生成工作目录（课题卡、笔记表、检索日志、版本谱系、论点表、大纲、检查表） |
| [`REFERENCES.md`](REFERENCES.md) | **参考文献**：本指南的编写依据，按 GB/T 7714—2025 顺序编码制著录 ｜ [在线版](https://nqd963.github.io/literature-review-writing/bib.html) |

---

## 安装：放进任何 harness 的 skills 目录

本仓库遵循 **Agent Skills 开放规范**，目录结构本身就是全部约定：

```
literature-review-writing/
├── SKILL.md              # 必需：name + description 的 YAML frontmatter，触发入口
├── references/           # 可选：按需渐进加载的分册
└── scripts/              # 可选：可执行的辅助脚本
```

**通用做法**：把整个目录复制到你的 harness 的 skills 目录下即可。常见位置（以各工具官方文档为准）：

| Harness | 用户级目录 | 项目级目录 |
|---|---|---|
| Claude Code | `~/.claude/skills/` | `.claude/skills/` |
| Codex CLI | `~/.codex/skills/` | `.codex/skills/` |
| WorkBuddy | `~/.workbuddy/skills/` | `.workbuddy/skills/` |
| Cursor / 其他遵循该规范的工具 | 见各自文档 | 项目内 `skills/` |

```bash
# 例：安装到 Claude Code
cp -r literature-review-writing ~/.claude/skills/
```

> 若你的工具只认单文件，也可以只拷贝 `SKILL.md`；但渐进加载的分册（`references/`）是大头，建议整体安装。

**触发方式**：装好后直接说"帮我写某某主题的文献综述""研究现状怎么写""开题报告的文献综述"即可。

**只想当作手册阅读**：打开[在线文档站](https://nqd963.github.io/literature-review-writing/)或直接看上面的 md 文件。

### 起手工具

```bash
python scripts/init_review_workspace.py <目标目录> \
  --topic "贾谊赋研究" --since 1980 --until 2025
```

生成 7 个文件：`project.md`（课题卡：三条边界 + 检索时间范围 + 建卡日期）、`notes.csv`（26 字段笔记表）、`search-log.csv`、`editions.csv`、`claims.csv`、`outline.md`、`checklist.md`。仅用标准库，CSV 带 BOM，Excel 双击不乱码。

`--since/--until` 会同时写进课题卡、大纲与检索日志示例行。**检索时间范围是综述最常漏、也最容易被答辩追问的一项**：说不出检索到哪一年，"研究空白"就不成立。省略 `--until` 时默认取当前年份。

---

## 几个最有价值的判断

<details>
<summary><b>① 古代评点不是"研究文献"，是"前研究史"</b></summary>

序跋、诗话、选本评语、年谱本身构成前研究史，**通代题目必须单列为第一部分**，形成"古代评点史 → 现代学术史"两段式。清人的一句评语和 2005 年一篇硕士论文不该平起平坐。

写这部分最省力的路径是《古典文学研究资料汇编》系列——陆游篇的古代评语几乎全出自《陆游资料汇编》一本（清代部分收录 158 家）。

</details>

<details>
<summary><b>② 结构与展开是两层，不要混着选</b></summary>

- **外层骨架**（全文统一）：学术史分期式 / 问题争议式 / 对象文体式 / 方法视角式 / 综合式。
- **内层手法**（可逐节不同）：循序、论证、分类、对比、归纳。

最常见的错是两层混用：目录看着是"问题式"，每节内部却按作者年代罗列，结果仍是流水账。
**检验：遮住目录只看每节首句——若都是"某某（年份）认为……"，说明内层退化成循序法而外层失效。**

</details>

<details>
<summary><b>③ 结语的"未来方向"应当就是你的选题</b></summary>

贾谊篇结语从"贾谊辞赋对先秦文学的继承与创变"这一空白，自然收到《鵩鸟赋》对《庄子》的文学性继承——那正是作者自己的科研创新项目。

反过来也成立：**写不出具体的未来方向，说明你还没找到选题**，回去重做"列争议清单"那一步。

</details>

<details>
<summary><b>④ 批评要指名道姓</b></summary>

"研究还不够深入"是空话；"高胜利两文相隔三年而内容基本重合"才是学术批评。点名不是为了刻薄，是为了让判断可核查。

四类常见毛病可直接当检查清单：重复研究创新不足 / 缺乏深层次分析 / 概念理解偏差 / 材料支撑不足轻下结论。

</details>

---

## 来源

- 骨架：Galvan, J. L. & Galvan, M. C. *Writing Literature Reviews*（第七版），中译本《文献综述写作》。**仅取其四阶段流程、综合纪律与评价标准，并已全部改写为古代文学语境；原书的章节编号、英文示例、附录逐条清单均未收录。** 需要完整方法论请直接读原书。见 [REFERENCES.md](REFERENCES.md)。
- 中文期刊体裁要件：陈立宏、李旭、吴永康、刘艳《关于研究生文献综述撰写的几点建议》，《教育教学论坛》2022 年第 31 期。
- 领域范例：李建英《陆游诗研究综述》（《北京青年政治学院学报》2009 年第 3 期）、李怡蕾《近四十年来贾谊赋研究综述》（《宁夏师范学院学报》2020 年第 8 期）。
- 引文规范：GB/T 7714—2025《信息与文献 参考文献著录规则》。
- 海外汉学人名与学派归属、部分范文参考文献条目转录自上述论文，**未逐条回查原刊**，相关处已标〔待核〕。

---

## 许可

MIT。欢迎 fork 后按你所在学校/刊物的具体规定调整体例细节。

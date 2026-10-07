# 来源署名与许可范围

文档修订 v0.2.1 / 2026-10-07。公开范围为 13 个文件，含一个 ChatGPT 生成的原创流程封面；原候选及历史记录保留。维护者及项目原创材料署名为 TUANZIDING。实际复用材料与设计参考分别说明，不把未复制的上游代码或技能写成已包含的依赖。

## 实际复制与修改

- `templates/review-template.md` 来源于 [2023Anita/evidence-gated](https://github.com/2023Anita/evidence-gated) 的本地文件 `examples/research-claim/review-template.md`。来源仓库提供 MIT 许可，版权声明 **Copyright (c) 2026 Anita**；适用许可和版权声明保留在 `LICENSE`。
- 原文件 SHA-256：`43c208e5e7e361306d0ffab58625ce693e984ddcb805f930d2095b77f893fa64`；本包模板 SHA-256：`89fd51f9620873d19a012a2a7f182da282aed6d540453baa350745492843776e`。相对原模板唯一正文变更：在可重复的证据块内新增“证据角色”一行，允许组合且不自动赋标签。本次公开展示改版保持模板字节不变。
- v0.1 来源记录标明该模板来自本地未提交文档；本轮保持候选模板字节，不宣称远端已发布该模板，不提供不存在的提交永久链接。来源与许可依据沿用既有实际文件记录，不是人员资格验证。
- `LICENSE` 保留来源仓库完整 MIT 授权/免责正文及 Anita 版权声明，并按用户确认增加 TUANZIDING 原创材料版权及范围说明。原末尾关于 `upstream/agent-skills/` 的说明未复制，因为本包没有该目录或内容。
- 未复制 Addy Osmani 的 `agent-skills`、布尔检查器、治理引擎、Schema、审批、CI 或可执行代码；不列为依赖。也未复制 nature 技能或工具实现。

## 原创材料署名与 MIT 范围

**Copyright (c) 2026 TUANZIDING** 适用于本项目原创文档及合成材料，包括 README、合成示例、自写案例审查摘要、角色回看、可选技能指导、文件清单、检查说明及原创流程封面；用户已确认按 MIT 授权。**Copyright (c) 2026 Anita** 保留复用模板材料的适用版权和 MIT 许可，不表示 Anita 对本项目作出科学判断或人工确认。

项目 MIT 只覆盖上述原创材料和按 MIT 实际复用的内容，不覆盖论文、图表、患者数据、外部技能或服务。项目署名不是历史审查身份核验，不将 TUANZIDING 回填为原复核者姓名或专家资质；历史人工确认的范围与版本绑定保持不变。

## 原创封面与布局参考

[assets/cover.png](assets/cover.png) 是按 TUANZIDING 选定的设计方向，使用 ChatGPT 内置图像生成制作的原创医学科技风格封面，署名 TUANZIDING，按本项目原创材料的 MIT 许可发布。尺寸 2172 × 724（3:1）。它展示“声明 → 原文证据 → 辅助判断 → 人工确认”，并注明辅助判断须人工复核。背景细胞/分子意象仅为装饰，不是论文插图或实验结果；未使用论文截图、患者信息、真实签章或外部仓库素材，不表示自动判断科学真伪或自动完成人工签认。PNG 为静态图片，不加载脚本或外部资源。旧 SVG 与生成提示词、摘要记录保存在仓库外，没有一并公开。

README 仅参考 [2023Anita/percolation-theory-visual-guide](https://github.com/2023Anita/percolation-theory-visual-guide) 的布局和信息顺序：封面、居中标题、中英副标题、简短标签、快捷入口、内容展示、边界与导航。本轮呈现设计阶段实际读取其公开首页，没有复制其封面、插画、正文或代码；该仓库不是本包包含的依赖，本项目 MIT 不覆盖其材料。

## 可选技能说明的设计参考

`docs/optional-skills.md` 是根据用户确认的草案新写的使用指导。设计参考为实际阅读的 codex-dynamic-workflows-enhanced、nature-reviewer、nature-statistics 使用说明，以及 evidence-gated 的工程范围、版本和检查原则；没有复制或摘录外部技能源码、脚本、模板或规则文件，没有迁移治理引擎。这些技能不是本包包含的依赖，不提供未经核实的技能版本、永久来源链接或人员资质。

外部技能自身的许可未在本轮核验；本包 MIT 不覆盖这些技能或 Elicit、scite 服务。未来如需实际复制材料，应先核对适用许可和署名。Elicit、scite 本轮不接入，未核验其服务能力或条款，也不是使用或发布本包的前提。新说明没有获得历史案例人工签认，旧确认不延伸到新技能意见。

## 文献引用（没有再分发论文内容）

1. **Neonatal muscle-derived extracellular vesicles containing miR-542-3p rejuvenate aged skeletal muscle via a functional microneedle patch**. Bioactive Materials 65 (2026), 573–592. [DOI: 10.1016/j.bioactmat.2026.06.011](https://doi.org/10.1016/j.bioactmat.2026.06.011). 提供 PDF 首页自述 © 2026 The Authors，CC BY-NC-ND 4.0。
2. **Clinical characteristics and mortality risk factors in polytrauma patients with pelvic fractures: a retrospective study based on an integrated multidisciplinary treatment approach**. International Journal of Emergency Medicine (2025) 18:192. [DOI: 10.1186/s12245-025-00990-5](https://doi.org/10.1186/s12245-025-00990-5). 提供 PDF 首页自述 © The Author(s) 2025，CC BY-NC-ND 4.0。

[CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/) 是论文各自声明的许可，不能将本包 MIT 描述为论文/图表/患者数据的授权。本包无论文短引文、全文或插图；候选句是测试表述，不声称全部为作者原话。摘要是自行撰写的范围和状态记录，不替代全文或原始数据。

文献元数据和 PDF 权利标记沿用 v0.1 来源记录，本轮未重新阅读论文或核验其许可标记。本轮呈现设计阶段只读取上述布局参考首页，未重新核验论文 DOI、历史来源或许可链接，原预检中的未核验事项仍保留；不对第三方材料或未来新增引文作许可保证。

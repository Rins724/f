# 自行车头盔设计 · 用户画像与用户旅程图 Skills

这个仓库收录五个 Skill，供自行车头盔设计项目制作用户画像、用户旅程图，装备使用研究，以及后续的视觉排版与提案展示。前两个来自 [Product on Purpose / PM-Skills](https://github.com/product-on-purpose/pm-skills)，第三个来自 [Dai Pan / Infographic Editorial Design](https://github.com/dpan538/infographic-editorial-design-skill)。

第四个来自 [cuevasclemente/mypi](https://github.com/cuevasclemente/mypi)，用于头盔与防护装备研究。

## 打开文件夹

| 用途 | Skill 文件夹 | 主说明 |
| --- | --- | --- |
| 用户画像 | [skills/foundation-persona](skills/foundation-persona/) | [SKILL.md](skills/foundation-persona/SKILL.md) |
| 用户旅程图 | [skills/discover-journey-map](skills/discover-journey-map/) | [SKILL.md](skills/discover-journey-map/SKILL.md) |
| 视觉排版与设计表达 | [skills/infographic-editorial-design](skills/infographic-editorial-design/) | [SKILL.md](skills/infographic-editorial-design/SKILL.md) |
| 头盔与防护装备使用研究 | [skills/e-bike-helmet-protective-gear-research](skills/e-bike-helmet-protective-gear-research/) | [SKILL.md](skills/e-bike-helmet-protective-gear-research/SKILL.md) |
| 中国头围头型国标与适配 | [skills/china-head-standards-fit](skills/china-head-standards-fit/) | [SKILL.md](skills/china-head-standards-fit/SKILL.md) |
| 填写人物与项目参数 | [project](project/) | [brief.md](project/brief.md) |

画像与旅程 Skill 各含主说明、输出模板和示例；视觉 Skill 包含设计原则、网格、风格定位、可读性和评估参考。上游文件保持原样，具体来源和版本见 [SOURCES.md](SOURCES.md)。

## 建议使用顺序

1. 填写 [project/brief.md](project/brief.md)，确定人物的年龄、骑行习惯、装备知识和旅程范围。已有信息无需重复填写。
2. 明确要求生成用户画像时，使用 `foundation-persona` 的 `product` 模式，生成一位主要骑行者的画像。
3. 明确要求生成旅程图时，使用 `discover-journey-map`，把前一步的画像、骑行目标和旅程起止点作为输入。
4. 分别保存为 `outputs/01-user-persona.md` 和 `outputs/02-user-journey-map.md`；上述路径是未来产出约定，目前仓库没有生成这两份成果。

5. 两份内容确认后，再使用 `infographic-editorial-design` 设计展示版。先确定展示媒介、尺寸、受众和视觉方向；保留用户画像与用户旅程图两份独立成果。

## 第三个 Skill：视觉排版与设计表达

[Infographic Editorial Design](skills/infographic-editorial-design/SKILL.md) 用于信息图、研究海报和编辑式信息展示，覆盖网格、字体、色彩、视觉层级、证据呈现和可读性评估。

在本项目中的用途：让甲方清楚看到用户是谁、骑行过程遇到什么问题、头盔有什么设计机会，以及方案依据是什么。页面设计需要说明为什么采用这种结构和视觉语言，并让重点结论容易找到。

它提供设计方法与检查标准。最终生成网页、图片、PDF 或演示文稿，需要按交付格式使用相应工具；收录文件不代表已经生成成品或执行了视觉评估。

## 第四个 Skill：头盔与防护装备研究

[E-Bike Helmet & Protective-Gear Research](skills/e-bike-helmet-protective-gear-research/SKILL.md) 覆盖头盔、眼镜、手套、鞋服及其舒适性、搭配与场景取舍，并要求核对产品证据。

它原本面向电助力自行车；本项目如研究普通自行车，应按实际车型和骑行情境使用。它没有完整覆盖码表、功率计等电子装备的操作体验。详见 [项目使用说明](skills/e-bike-helmet-protective-gear-research/PROJECT-USAGE.md)，其中提供工具适配与中文调用指令。

## 头盔项目怎么使用

- 产品对象：实体自行车头盔。流程应关注真实接触点，例如试戴、系带调节、与骑行眼镜搭配、骑行中的体验、清洁与收纳。
- 画像选择 `product` 模式。模板中公司规模、汇报关系等与个人骑行无关的字段可写“与本项目无关”，不要为填表编造背景。
- 旅程可以覆盖一次完整骑行周期，也可以覆盖选购到首次使用；先填写起点、终点和目标。
- 可以使用虚构骑行者做早期设计模拟。人物设定要注明“用户指定的虚构设定”；没有研究支持的行为、情绪和痛点要标为“假设 / 待验证”，不能写成真实访谈结论。
- 引用骑行装备功能、品牌参数和产品资料时应核对来源。产品说明可以证明装备功能，不能证明骑手的习惯或感受。
- 上游示例用于参考结构，示例中的人名、访谈和数据不能作为本项目证据。
- 打开或保存这些文件不代表执行 Skill。请在人物设定完成后，明确指示开始哪一份产出。

## 可复制的使用指令

**只整理设定：**

> 阅读 project/brief.md，只整理我已填写的人物设定，并指出空缺项。先不要生成用户画像或旅程图。

**生成用户画像：**

> 阅读 skills/foundation-persona/SKILL.md 及它的 references/TEMPLATE.md，以 product 模式为自行车头盔项目制作一位主要骑行者的用户画像。使用 project/brief.md。将虚构设定、设计假设和真实研究证据标清楚，输出到 outputs/01-user-persona.md。

**生成用户旅程图：**

> 阅读 skills/discover-journey-map/SKILL.md 及它的 references/TEMPLATE.md，以 outputs/01-user-persona.md 和 project/brief.md 为输入，制作自行车头盔用户旅程图。遵守已选择的旅程起止点，将无研究支持的情绪与痛点标为假设，输出到 outputs/02-user-journey-map.md。

**制作视觉展示版（内容确认后）：**

> 阅读 skills/infographic-editorial-design/SKILL.md 及相关 references，以确认后的用户画像与旅程图为内容，为自行车头盔提案设计两份独立展示稿。先确认交付格式与尺寸，提出适合甲方受众的视觉方向，说明网格、字体、配色和信息层级的理由。清楚呈现用户问题、设计机会与方案价值，保留假设和证据标注，不添加未经支持的数据或引语。

## 文件与运行环境

这些 Skill 以 Markdown 指令为主，不需要扫描软件代码库，也不依赖你之前贴出的 Journey Mapper 的 build.py 或 HTML 模板。旅程 Skill 支持 Markdown 表格和 Mermaid 图；不会自动生成那个 Skill 的交互式 HTML。

上游提到的其他研究、图表和评审 Skills 是扩展工作流，本仓库收录这两个 Skill 的主说明、必要模板和本地示例，另外完整收录第三个视觉设计 Skill 的文本文件。遇到需要额外 Skill 的任务，应先说明缺少的工具，不能声称已经运行。

在 GitHub 的“代码 / Code”页可以浏览全部文件夹。要在电脑的项目中看到文件，需要克隆或同步此仓库；仓库保存本身不会将 Skill 自动安装到本地应用。

## 来源与许可

- 画像与旅程：[product-on-purpose/pm-skills](https://github.com/product-on-purpose/pm-skills)，保留 [Apache License 2.0](LICENSE)。
- 视觉设计：[dpan538/infographic-editorial-design-skill](https://github.com/dpan538/infographic-editorial-design-skill)，保留该目录内的 [MIT 许可证及第三方材料说明](skills/infographic-editorial-design/LICENSE)。

- 装备研究：[cuevasclemente/mypi](https://github.com/cuevasclemente/mypi)，保留该目录内的 [MPL-2.0 许可证](skills/e-bike-helmet-protective-gear-research/LICENSE)。

各来源文件按各自许可证使用，原作者归属、固定版本和来源链接记录在 [SOURCES.md](SOURCES.md)。

## 中国头围头型国标与适配

新增 [china-head-standards-fit](skills/china-head-standards-fit/SKILL.md)，与装备研究 Skill 分开。以 GB/T 2428-2024《成年人头面部尺寸》和适用的三维头型标准为依据，研究头围、头长、头宽、尺码与人群适配。它是本仓库新编的研究指引，原始尺寸需从官方标准正文核对；当前没有预填标准尺寸表，也不凭尺寸匹配判断头盔整体合格。

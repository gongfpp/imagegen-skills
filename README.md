# 城下秋草 · 图片生成 Skill & Prompt

从我的 ChatGPT 原对话整理的生图提示词，重点是**前端设计参考图鉴**：网页风格、组件、按钮动效、页面转场和 Landing Page。也收录系列拟人插画与个人封面 Skill。

**小白直接复制 prompt 即可，不需要会写代码，也不需要先安装 Skill。**

## 大家最常用的：前端网页设计风格参考 01–04

> [!IMPORTANT]
> **来领取「前端网页设计美术风格参考图鉴」的朋友，直接打开下面这份。**
> **4 张独立图片 × 每张 5 种网页风格 = 20 种风格，3:4 竖版，页码 01–04。**

### 👉 [点击领取完整 Prompt：前端网页设计风格参考 01–04](skills/aki-design-reference/references/web-style-01-04.md)

**[直接打开纯文本，全选复制](https://raw.githubusercontent.com/gongfpp/imagegen-skills/main/skills/aki-design-reference/references/web-style-01-04.md)**

这份 prompt 的开头是：「生成一组『前端网页设计美术风格参考图鉴』，共生成 4 张独立的竖版长图，每张图片包含 5 种不同网页设计风格，共 20 种。」

内容包括极简主义、瑞士国际主义、杂志编辑风、玻璃拟态、Bento Grid、拟物、粗野主义、复古互联网、Y2K、赛博朋克、手绘和像素游戏风等 20 种风格。复制全文，粘贴给支持生图的 AI 即可使用。

继续扩展时，可领取[下一批网页风格 05–08](skills/aki-design-reference/references/web-style-05-08.md)。

## 先选你要的内容

| 想做什么 | 点击查看原文 | 默认输出 |
|---|---|---|
| **最常用：前端网页设计美术风格参考** | **[领取 01–04 完整 Prompt](skills/aki-design-reference/references/web-style-01-04.md)** | **4 张独立图片，共 20 种风格** |
| 同一个组件尝试不同美术风格 | [美术风格参考图鉴](skills/aki-design-reference/references/design-style-10-pages.md) | 10 张，每张 5 个案例 |
| 研究组件有哪些结构与功能 | [功能分类参考图鉴](skills/aki-design-reference/references/design-pattern-10-pages.md) | 10 张，每张 5 个案例 |
| 只复用布局，自选设计主题 | [通用图鉴母版](skills/aki-design-reference/references/layout-master-4-pages.md) | 4 张，每张 5 个案例 |
| 扩展更多网页首页风格 | [下一批 05–08](skills/aki-design-reference/references/web-style-05-08.md) | 4 张，共 20 种扩展风格 |
| 按钮动效 | [01–04](skills/aki-design-reference/references/button-motion-01-04.md) · [05–08](skills/aki-design-reference/references/button-motion-05-08.md) | 每批 4 张 |
| 页面转场与 Motion Design | [页面转场参考](skills/aki-design-reference/references/page-transition-motion-01-04.md) | 4 张 |
| Landing Page / 落地页 | [落地页参考](skills/aki-design-reference/references/landing-page-01-04.md) | 4 张 |
| Navbar / 导航栏 | [导航栏参考](skills/aki-design-reference/references/navbar-01-04.md) | 4 张 |

十页通用版中，“美术风格”用来比较同一对象的视觉语言；“功能分类”用来比较类型、结构与交互方式。它们适合自选主体；领取上方常用网页图鉴时，选择四页的 01–04 版本。

## 第一次使用

1. 领取常用网页图鉴时，点击首页上方的 **「前端网页设计风格参考 01–04」**；其他主题按上表选择。
2. 打开文件后，点击 **Raw** 查看纯文本；全选并复制。也可以直接复制页面中的正文。
3. 粘贴到你使用的、支持图片生成的 AI 工具里，再补充具体主题。
4. 如果一次没有生成全部图片，继续要求生成下一页，并明确页码。模板里的数量是目标，实际交付取决于工具能力与额度。

复制常用的「前端网页设计风格参考 01–04」全文后，可以补一句：

> 请按这份 prompt 生成 4 张独立图片，每张 5 种网页设计风格，页码为 01–04。每次只生成一页，从第 01 页开始。

如果需要搜索框、导航栏等其他主体，可选择十页通用版；只想要文字时可以写：

> 本次主体是搜索框 Search Bar。请按这份模板整理生图 prompt，先不要生成图片。

按钮动效和页面转场的图片是静态参考，会用关键帧、路径与状态标签说明运动；实际动画需要后续实现。

![GitHub 领取与使用教程](docs/github-guide.png)

## 下载与安装 Skill

点击仓库首页绿色 **Code → Download ZIP**，解压后打开 `skills/`。手机如果看不到 Code 按钮，可以切换电脑浏览器。也可[直接下载 ZIP](https://github.com/gongfpp/imagegen-skills/archive/refs/heads/main.zip)。

| Skill 文件夹 | 用途 |
|---|---|
| [aki-design-reference](skills/aki-design-reference/SKILL.md) | 设计图鉴、网页风格、组件与动效参考 |
| [aki-gijinka-illustration](skills/aki-gijinka-illustration/SKILL.md) | 饮料、食品与软件系列拟人插画 |
| [aki-rednote-cover](skills/aki-rednote-cover/SKILL.md) | 个人封面，保留三颗草和“城下秋草” |

将需要的**整个文件夹**放进你的 Agent 支持的 skills 目录，保留 `SKILL.md` 和 `references/` 的相对位置。具体目录以所用工具为准；没有 Skill 支持也可以直接使用 prompt。

前两个 Skill 是本次发布时新增的安装入口，内部 prompt 来源于原对话；封面 Skill 使用本机当前版本。

## 其他生图 prompt

| 主题 | 原文 |
|---|---|
| 饮料拟人 | [九款饮料，防重复优化版](skills/aki-gijinka-illustration/references/drinks-gijinka.md) |
| 瓶装水拟人 | [国产瓶装水](skills/aki-gijinka-illustration/references/bottled-water-gijinka.md) |
| 地方美食拟人 | [中国地方美食](skills/aki-gijinka-illustration/references/regional-food-gijinka.md) |
| 辣条拟人 | [辣条系列](skills/aki-gijinka-illustration/references/latiao-gijinka.md) |
| 冰淇淋拟人 | [冰淇淋系列](skills/aki-gijinka-illustration/references/ice-cream-gijinka.md) |
| 软件拟人 | [国产互联网与软件](skills/aki-gijinka-illustration/references/software-gijinka.md) |

## 来源与版本

本次收录 17 份完整 prompt、3 个 Skill 入口。原文只去掉 ChatGPT 的 writing 包装或最外层 Markdown 代码围栏，未把旧版四页 prompt 改成十页。旧版放在明确的历史路径，按所需系列选择。

来源日期、提取方式与文件 SHA-256 见 [sources.json](docs/sources.json)。读取范围与未取到的附件见[来源说明](docs/sources.md)。这里只收录本次能完整取到的文本，不代表全部历史生图聊天均已归档。

文本与 Skill 使用 [MIT License](LICENSE)，可以使用、修改和分享，保留许可证即可。品牌主题为虚构创作练习，不表示品牌背书；仓库没有打包第三方参考图、字体、商标素材或官方系统 Skill。生成图片的使用还需遵守所用工具的条款。

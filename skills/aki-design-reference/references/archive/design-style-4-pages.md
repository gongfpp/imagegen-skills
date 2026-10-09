# 通用设计美术风格参考图鉴生成 Prompt

生成一套围绕指定设计主体的 **「美术风格参考图鉴」**。

共生成 **4 张彼此独立的图片，每张包含 5 个案例，共 20 个案例**。

本 Prompt 只固定：

- 图鉴整体版式
- 输出数量
- 视觉系统
- 美术风格变化原则
- 案例展示方式

具体设计主体由执行 Agent 根据用户当次任务自行确定。

设计主体可以是：

- Navbar / 导航栏
- Button / 按钮
- Input / 输入框
- Search Bar / 搜索框
- Menu / Dropdown
- Tab / Segmented Control
- Card
- Modal
- Sidebar
- Header
- Footer
- Landing Page
- Dashboard
- Game UI
- App 页面
- 完整网页
- 其他任何 UI / Web / App / Game 设计对象

---

# 一、核心任务

本图鉴的核心不是展示：

> 这个设计主体有哪些功能类型、结构类型或交互类型。

而是展示：

> **同一种设计主体，在不同美术风格、视觉语言和艺术方向下，可以被设计成什么样子。**

例如，当主题为 Navbar 时，不应该把主要案例分类设计成：

- 顶部导航
- 侧栏导航
- Mega Menu
- Sticky Nav
- Dropdown Nav

这种分类主要属于 **结构与功能差异**。

更应该展示：

- Swiss / 瑞士国际主义风 Navbar
- Neo-Brutalism / 新粗野主义风 Navbar
- Glassmorphism / 玻璃拟态 Navbar
- Y2K / 千禧未来主义 Navbar
- Editorial / 杂志编辑风 Navbar

也就是说：

**主体保持 Navbar，变化的是设计语言。**

当主题为 Button 时，同理不要主要按照：

- Loading Button
- Submit Button
- Icon Button
- Download Button
- Toggle Button

分类。

而应该按照不同美术语言重新设计同类按钮。

当主题为 Landing Page 时，也不是主要展示：

- SaaS Landing Page
- 产品页
- Waitlist Page
- Pricing Page

而应该展示同类 Landing Page 在不同视觉风格下的设计表现。

---

# 二、最重要的变量：美术风格

20 个案例之间的主要区别必须来自：

- 色彩体系
- 字体体系
- 图形语言
- 边框语言
- 圆角语言
- 材质
- 阴影
- 光影
- 纹理
- 图标
- 插画
- 摄影
- 留白
- 信息密度
- 网格
- 排版方式
- 几何形态
- 装饰语言
- 时代审美
- 品牌气质
- 空间感
- 视觉层级

结构与功能允许根据风格做适度调整，但这些变化只是 **服务于视觉风格表达**。

禁止仅仅通过：

- 换位置
- 换菜单数量
- 换功能
- 换文案
- 换组件类型

来制造所谓的“不同案例”。

如果把所有案例去掉颜色以后，看起来仍然几乎完全相同，说明风格差异不足。

如果案例之间只是功能不同，而字体、形态、色彩、材质、视觉语言几乎一致，也判定为失败。

---

# 三、风格选择原则

执行 Agent 根据当前设计主体，从适合该主体的视觉风格中自主挑选 **20 种具有明显区分度的美术风格**。

20 个案例不得重复。

同一大类下面非常相似的风格，不要连续占用大量名额。

例如不要出现：

- Minimal
- Clean Minimal
- Modern Minimal
- Soft Minimal
- Simple Minimal

然后把它们当成 5 个不同案例。

不同案例应尽可能覆盖不同视觉谱系。

可以参考但不限于以下风格池：

## 现代与理性

- Minimalism / 极简主义
- Swiss Style / 瑞士国际主义
- International Typographic Style / 国际主义排版
- Grid-based Modernism / 网格现代主义
- Functionalism / 功能主义
- Corporate Modern / 企业现代风

## 编辑与文化

- Editorial / 杂志编辑风
- Newspaper / 报刊风
- Fashion Editorial / 时尚编辑风
- Art Book / 艺术画册风
- Typography-led / 字体主导风
- Monochrome Editorial / 黑白编辑风

## 粗犷与实验

- Brutalism / 粗野主义
- Neo-Brutalism / 新粗野主义
- Experimental Typography / 实验字体
- Deconstruction / 解构主义
- Anti-design / 反设计
- Maximalism / 极繁主义

## 科技与未来

- Dark Tech / 黑色科技极简
- Cyberpunk / 赛博朋克
- Futurism / 未来主义
- Retrofuturism / 复古未来主义
- Sci-Fi HUD / 科幻 HUD
- Holographic / 全息风
- AI-native / AI 原生视觉

## 半透明与空间

- Glassmorphism / 玻璃拟态
- Frosted Glass / 磨砂玻璃
- Layered Transparency / 层叠透明
- Aurora / 极光渐变
- Gradient Mesh / 渐变网格

## 实体与质感

- Skeuomorphism / 拟物主义
- Neumorphism / 新拟态
- Claymorphism / 黏土拟物
- Soft UI / 柔和 UI
- Metallic / 金属质感
- Paper Texture / 纸张质感
- Ceramic / 陶瓷质感

## 复古与年代

- Retro Web / 复古互联网
- Y2K / 千禧未来主义
- Web 1.0
- Windows 95 / 98 风
- Macintosh Classic 风
- Vaporwave / 蒸汽波
- Synthwave / 合成波
- 70s Graphic
- 80s Memphis
- 90s Digital

## 艺术与图形

- Bauhaus / 包豪斯
- Memphis / 孟菲斯
- Constructivism / 构成主义
- Abstract Geometry / 抽象几何
- Collage / 拼贴
- Paper Cut / 剪纸
- Pop Art / 波普艺术
- Psychedelic / 迷幻
- Op Art / 欧普艺术

## 插画方向

- Hand-drawn / 手绘
- Monoline / 单线插画
- Flat Illustration / 扁平插画
- Isometric / 等距插画
- 3D Illustration
- Low-poly
- Cartoon
- Comic / 漫画风
- Pixel Art / 像素风

## 自然与生活

- Organic / 有机风
- Eco / 自然生态
- Japandi / 日式极简
- Wabi-sabi / 侘寂
- Scandinavian / 北欧
- Cottagecore / 田园
- Botanical / 植物风

## 高端与品牌

- Luxury Minimal / 奢华极简
- Quiet Luxury / 静奢
- Premium Editorial
- Black & Gold
- High-fashion
- Architectural Minimal

这里只是 **风格候选库**。

执行 Agent不需要机械地按照这个列表排序，也不要求每次都使用相同 20 种。

应该根据具体主体判断：

> 哪些风格用于这个设计对象时，能产生最有参考价值、最明显、最好看的视觉差异。

---

# 四、20 个案例必须做真正的风格重设计

每个案例不能只是：

> 普通 UI + 一个背景颜色。

需要根据对应风格重新考虑整个设计对象。

至少从以下维度中的多个方面同时发生改变：

### Typography

- Serif / Sans-serif / Mono / Display
- 字重
- 字号
- 字距
- 大小写
- 字体比例
- 文字方向
- 排版节奏

### Color

- 主色
- 辅助色
- 强调色
- 对比关系
- 明暗
- 色彩饱和度

### Shape

- Sharp
- Rounded
- Pill
- Geometric
- Organic
- Irregular

### Border

- 无边框
- Hairline
- 粗黑边框
- Double Border
- Pixel Border
- Decorative Border

### Shadow

- 无阴影
- Soft Shadow
- Hard Shadow
- Inner Shadow
- Glow
- Colored Shadow

### Material

- Flat
- Glass
- Metal
- Plastic
- Paper
- Clay
- Ceramic
- Fabric
- CRT
- Chrome

### Graphic Language

- Grid
- Geometry
- Pattern
- Sticker
- Doodle
- Pixel
- Noise
- Grain
- Halftone
- Collage

### Space

- 极简留白
- 高密度
- 层叠
- 漂浮
- 空间纵深
- 强二维平面感

风格变化必须是系统性的。

---

# 五、功能保持基本可比

为了让用户真正比较“美术风格”，不同案例应尽量维持 **相似的基础功能语义**。

例如主题是 Button：

可以都用类似：

> Get Started

作为主要按钮示例。

主题是 Navbar：

大部分案例可以保持类似：

> Logo  
> Products  
> Solutions  
> Resources  
> About  
> Get Started

主题是 Search Bar：

可以保持类似：

> Search anything...

这样观看者主要感受到的是：

**设计风格发生了变化。**

而不是：

**每个案例展示了完全不同的功能。**

允许为了适配风格对文案和内容做适量调整，但不能靠大规模改变功能制造视觉区别。

---

# 六、图片数量与输出形式

必须生成：

**4 张独立图片。**

每张：

**3:4 竖版。**

每张包含：

**5 个案例。**

共：

**20 个不同美术风格案例。**

输出形式：

```text
Image 1 = [主题名称]设计风格参考 01
Image 2 = [主题名称]设计风格参考 02
Image 3 = [主题名称]设计风格参考 03
Image 4 = [主题名称]设计风格参考 04
```

禁止：

- 四宫格
- 2×2 拼图
- Contact Sheet
- 超长图
- 一张图包含四张完整图鉴
- 生成之后要求用户手动裁切

必须进行 **4 次独立图片生成**。

每次只生成当前一页。

---

# 七、统一外层图鉴设计

注意区分：

> 图鉴本身的设计

和：

> 图鉴里面案例的设计。

## 图鉴外层

4 张图片完全统一。

使用：

- 浅暖灰白背景
- 高级设计书籍式排版
- 统一边距
- 统一标题
- 统一编号
- 统一字体层级
- 统一案例高度
- 统一左右比例
- 统一分隔线
- 克制装饰

外层图鉴不要随着案例风格变化。

## 案例内部

必须充分变化。

例如：

同一页可以出现：

- 极简黑白
- 粗黑描边高饱和
- 半透明玻璃
- Y2K Chrome
- 纸张拼贴

它们应该明显看起来属于 **5 套不同视觉系统**。

这是整套图鉴最重要的地方。

---

# 八、页面顶部

顶部约占整张图片高度的 10%–12%。

左上角主标题：

```text
[设计主体名称]设计风格参考 01
```

后续：

```text
[设计主体名称]设计风格参考 02
[设计主体名称]设计风格参考 03
[设计主体名称]设计风格参考 04
```

英文副标题：

```text
DESIGN STYLE REFERENCE
```

也可以根据主题改成：

```text
NAVBAR DESIGN STYLE REFERENCE
BUTTON DESIGN STYLE REFERENCE
LANDING PAGE STYLE REFERENCE
```

右上角可以加入：

```text
探索不同视觉语言
建立更完整的设计审美

STYLE
FORM
VISUAL LANGUAGE
```

辅助文字保持很小。

---

# 九、每张图片内部结构

每页固定包含 **5 个横向案例区域**。

从上向下排列。

每个案例结构完全一致：

## 左侧信息区

约占：

**25%–28%**

显示：

### 编号

```text
01
```

### 风格英文名

例如：

```text
Neo-Brutalism
```

### 中文名称

```text
新粗野主义
```

### 英文关键词

例如：

```text
BOLD
OUTLINE
COLOR
HARD SHADOW
```

### 中文关键词

```text
粗描边
高饱和
硬阴影
强对比
```

左侧文字主要回答：

> 这是什么美术风格？

不要在这里大量解释具体功能。

---

# 十、右侧演示区

约占：

**72%–75%**

右侧展示：

> 当前设计主体在这一种美术风格下的完整视觉实例。

重点是：

**把同一个主体重新设计。**

如果主题是 Navbar：

右侧主要展示 Navbar 与必要的页面背景。

如果主题是 Button：

右侧主要展示按钮及必要的使用环境。

如果主题是 Input：

放大展示输入框本身以及 Label、Placeholder、Focus 等必要状态。

如果主题是完整 Landing Page：

则展示完整 Landing Page 首屏。

右侧演示主体必须足够大。

不能为了表现“真实网页”而把对象缩得非常小。

---

# 十一、组件与局部元素主题的特殊要求

如果当前设计主体属于：

- Navbar
- Button
- Input
- Search
- Dropdown
- Tab
- Card
- Modal
- Checkbox
- Switch
- Slider

等局部 UI 元素，

不要让完整网页抢走视觉焦点。

应该：

> 用少量页面环境说明组件如何使用，同时大面积展示组件本身。

例如 Navbar：

Navbar 应占演示框非常重要的视觉面积。

下面只保留 Hero 的一部分，帮助理解背景关系。

例如 Button：

可以将一个或多个按钮放大展示。

页面背景仅作为辅助。

---

# 十二、完整页面主题的特殊要求

如果主体属于：

- Landing Page
- Dashboard
- Portfolio
- Blog
- E-commerce
- Game Website
- App Screen

则可以展示更完整的页面结构。

但是不同案例之间的主要区别仍然必须是：

**美术风格。**

而不是：

- 一个是商城
- 一个是博客
- 一个是后台
- 一个是新闻站

导致完全失去横向比较意义。

---

# 十三、状态与交互

如果设计主体天然具有状态：

例如：

- Button
- Input
- Dropdown
- Tab
- Toggle
- Menu

可以适量展示：

```text
DEFAULT
HOVER
ACTIVE
FOCUS
OPEN
SELECTED
```

但状态不是主要分类依据。

例如：

不要把：

```text
Default Button
Hover Button
Active Button
Loading Button
Disabled Button
```

做成五个所谓“风格”。

同一个案例内部可以展示必要状态。

不同案例之间主要仍然比较：

**美术风格。**

---

# 十四、案例差异检查

生成前先检查 20 个风格。

任何两个案例如果高度相似，应主动替换其中一个。

检查维度包括：

- 配色是否高度相似
- 字体是否高度相似
- 圆角是否高度相似
- 边框是否高度相似
- 材质是否高度相似
- 信息密度是否高度相似
- 图形语言是否高度相似
- 时代气质是否高度相似

例如以下情况应避免：

```text
Minimalism
Modern Minimal
Soft Minimal
Clean Minimal
Premium Minimal
```

这种看似五个名字，实际是一种设计语言。

更好的组合应该具有明显跨度，例如：

```text
Swiss
Neo-Brutalism
Glassmorphism
Y2K
Editorial
```

---

# 十五、不要让 AI 默认审美吞掉所有风格

特别避免所有案例最终都变成：

- 大圆角
- 白色 Card
- 蓝紫渐变
- Glassmorphism
- Inter / 类似无衬线字体
- Pill Button
- 左文字右图片
- Bento Grid
- Soft Shadow
- AI SaaS 风

如果当前案例是：

**Brutalism**

就真正采用粗野主义。

如果是：

**Retro Web**

就真正体现早期互联网视觉。

如果是：

**Editorial**

就真正使用杂志式排版体系。

如果是：

**Y2K**

就真正出现 Chrome、半透明塑料、Liquid Form 等语言。

如果是：

**Bauhaus**

就真正体现基础几何与构成。

不要只在左侧写一个风格名称，右侧仍然画成普通现代 SaaS UI。

---

# 十六、避免重复

20 个案例必须：

**没有重复风格。**

名称不同但视觉结果基本相同也视为重复。

执行 Agent 在分配四张图片之前，先规划完整 20 个风格，再分为：

```text
01：5 个
02：5 个
03：5 个
04：5 个
```

避免生成到后面才发现与前面重复。

四页之间也不能重复。

---

# 十七、文字与案例真实性

示例中的产品、品牌和页面均使用虚构内容。

不要复制真实品牌。

不要编造：

- 用户数
- 获奖情况
- 市占率
- 客户背书

如果这些信息只是视觉占位，应保持明显的虚构或通用性质。

文字要：

- 短
- 清楚
- 可读
- 服务视觉

不要塞入大量正文。

---

# 十八、质量检查

最终检查以下内容：

### 页面

- 是否为 4 张独立图片
- 是否都是 3:4
- 是否每张正好 5 个案例
- 是否统一图鉴模板
- 是否页码连续

### 风格

- 是否恰好 20 个不同美术风格
- 是否没有重复
- 是否视觉区别足够大
- 是否真正重新设计了主体
- 是否避免全部变成现代 SaaS 风

### 主体

- 是否所有案例仍然在展示同一种指定设计主体
- 是否没有偷偷把“风格分类”变成“功能分类”
- 是否没有因为展示完整页面而让主体过小

### 文字

- 中英文名称是否准确
- 编号是否正确
- 是否没有乱码
- 是否没有未替换的 `[主题名称]`
- 是否没有多余占位符

---

# 十九、最终执行原则

整个任务遵循一个核心原则：

> **外层图鉴统一，内部案例多样。**

图鉴的：

- 背景
- 标题
- 网格
- 信息层级
- 编号
- 间距

保持一致。

案例内部的：

- 字体
- 配色
- 形状
- 材质
- 纹理
- 图形
- 排版
- 阴影
- 视觉密度
- 艺术方向

必须根据不同美术风格充分变化。

最终目标不是告诉用户：

> “这个组件有 20 种功能。”

而是让用户直观看到：

> **“同一个设计对象，可以拥有 20 种完全不同的美术表达。”**

---

# 二十、最终输出

分别执行 4 次图片生成：

```text
第一次：
只生成 [设计主体名称]设计风格参考 01

第二次：
只生成 [设计主体名称]设计风格参考 02

第三次：
只生成 [设计主体名称]设计风格参考 03

第四次：
只生成 [设计主体名称]设计风格参考 04
```

每次：

```text
n = 1
```

每次只生成：

**1 张 3:4 图片 × 5 个案例。**

最终得到：

**4 张独立图片 × 5 个风格 = 20 个不同美术风格案例。**

禁止将 4 页合并成一张图。

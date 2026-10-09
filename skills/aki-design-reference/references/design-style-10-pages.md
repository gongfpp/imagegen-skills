# 通用设计美术风格参考图鉴生成 Prompt

生成一套围绕指定设计主体的 **「美术风格参考图鉴」**。

共生成：

**10 张彼此完全独立的图片。**

每张图片包含：

**5 个美术风格案例。**

总计：

**10 张图片 × 5 个案例 = 50 个不同美术风格案例。**

本 Prompt 只固定：

- 图鉴整体版式
- 输出数量
- 页码规则
- 视觉系统
- 美术风格变化原则
- 案例展示方式

具体设计主体由执行 Agent 根据用户当次任务确定。

设计主体可以是但不限于：

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
- 其他 UI / Web / App / Game 设计对象

---

# 一、核心任务

本 Prompt 的核心目标是：

> **同一种设计主体，在 50 种不同美术风格、视觉语言和艺术方向下，会呈现出什么样的设计。**

主要变量必须是：

**美术风格。**

不能把主要变化做成功能、结构或者交互方式。

例如主题是 Navbar，不应主要按照：

- 顶部导航
- 侧栏导航
- Mega Menu
- Sticky Navbar
- Dropdown Navbar

来分类。

这些属于功能或结构差异。

正确方向应该类似：

- Minimalism / 极简主义 Navbar
- Swiss / 瑞士国际主义 Navbar
- Editorial / 编辑风 Navbar
- Neo-Brutalism / 新粗野主义 Navbar
- Glassmorphism / 玻璃拟态 Navbar
- Y2K / 千禧未来主义 Navbar
- Retro Web / 复古互联网 Navbar
- Cyberpunk / 赛博朋克 Navbar
- Bauhaus / 包豪斯 Navbar
- Memphis / 孟菲斯 Navbar

即：

> **主体保持基本一致，改变视觉语言。**

---

# 二、图片数量——必须是 10 张独立图片

最终必须得到：

```text
Image 01
Image 02
Image 03
Image 04
Image 05
Image 06
Image 07
Image 08
Image 09
Image 10
```

共 **10 个独立图片文件**。

每一个 Image 都必须是一个单独的：

**3:4 竖版图鉴页面。**

每张包含：

**5 个案例。**

---

# 三、极其重要：禁止拼图

绝对禁止生成：

- 10 页拼成一张长图
- 5×2 拼图
- Contact Sheet
- 总览图
- 多页缩略图集合
- 一张图片内部放 10 个完整页面
- 一张大图生成后再让用户裁切
- 一张图片同时出现「参考 01～10」十个完整页面

必须执行：

**10 次独立图片生成。**

每一次：

```text
n = 1
```

每一次只负责当前一页。

最终交付：

**10 个独立图片文件。**

不是：

**1 个包含 10 页的大文件。**

---

# 四、极其重要：页码必须连续且唯一

标题中的页码是：

**整张图鉴页面的页码。**

10 张图片必须严格按顺序使用：

```text
第 1 张： [主题名称]美术风格参考 01
第 2 张： [主题名称]美术风格参考 02
第 3 张： [主题名称]美术风格参考 03
第 4 张： [主题名称]美术风格参考 04
第 5 张： [主题名称]美术风格参考 05
第 6 张： [主题名称]美术风格参考 06
第 7 张： [主题名称]美术风格参考 07
第 8 张： [主题名称]美术风格参考 08
第 9 张： [主题名称]美术风格参考 09
第 10 张：[主题名称]美术风格参考 10
```

### 严禁出现

```text
第 1 张：XXXX参考 01
第 2 张：XXXX参考 01
第 3 张：XXXX参考 01
第 4 张：XXXX参考 01
...
```

每张图片标题中的页码都必须不同。

**01 只能出现于第 1 张。**

**02 只能出现于第 2 张。**

依次类推。

**10 只能出现于第 10 张。**

生成当前页之前必须先确认当前页面编号。

不得因为独立调用图片生成，而把每次都重新初始化为 01。

---

# 五、页码与案例编号必须区分

这里存在两套不同编号：

## 页面编号

表示这张图片是整个系列的第几页：

```text
01
02
03
...
10
```

它出现在顶部主标题中。

例如：

```text
导航栏美术风格参考 06
```

表示：

**这是整个系列的第 6 张独立图片。**

---

## 案例编号

每张图片内部固定有 5 个案例。

案例编号仍然使用：

```text
01
02
03
04
05
```

这只是当前页面内部的案例序号。

因此第 6 页可以出现：

```text
顶部标题：
导航栏美术风格参考 06

内部案例：
01
02
03
04
05
```

不要把案例编号误认为页面编号。

也不要因为案例从 01 开始，就把顶部页码重新改成 01。

---

# 六、整体版式

10 张图片全部使用完全一致的图鉴母版。

画面：

**3:4 竖版。**

背景：

**非常浅的暖灰白。**

视觉气质：

- Design Reference Book
- UI/UX Design Handbook
- Editorial Design
- 高级设计图鉴
- 专业设计教材

四周保持统一边距。

避免大量装饰。

---

# 七、顶部标题区域

顶部约占整张图片高度的：

**10%–12%。**

左上角：

```text
[主题名称]美术风格参考 XX
```

其中：

```text
XX = 当前页面编号
```

必须严格依次为：

```text
01 → 02 → 03 → 04 → 05 → 06 → 07 → 08 → 09 → 10
```

英文副标题：

```text
DESIGN STYLE REFERENCE
```

也可以根据主题使用：

```text
NAVBAR DESIGN STYLE REFERENCE
BUTTON DESIGN STYLE REFERENCE
INPUT DESIGN STYLE REFERENCE
LANDING PAGE DESIGN STYLE REFERENCE
```

右上角可以加入：

```text
探索不同视觉语言
建立完整设计审美

STYLE
FORM
VISUAL LANGUAGE
```

辅助文字保持很小。

---

# 八、每页固定 5 个案例

标题区域下方，从上至下排列：

**5 个横向案例。**

每个案例高度统一。

案例之间使用：

- 留白
- 极细浅灰分隔线

进行区分。

不要给每个案例再套一层厚重卡片。

---

# 九、每个案例的布局

每个案例采用：

> 左侧信息区 + 右侧演示区

### 左侧

约占：

**25%–28%。**

包含：

```text
案例编号

英文风格名称
中文风格名称

英文关键词
中文关键词
```

例如：

```text
03

Neo-Brutalism
新粗野主义

BOLD
OUTLINE
COLOR
HARD SHADOW

粗描边
高饱和
硬阴影
强对比
```

左侧回答：

> **这是哪一种美术风格？**

不要在这里主要解释功能。

---

# 十、右侧演示区

约占：

**72%–75%。**

这里展示：

> **当前设计主体在这一种美术风格下，被完整重新设计后的视觉效果。**

右侧主体必须足够大。

不要为了模拟完整网站把主体缩得非常小。

局部 UI 组件主题：

例如 Navbar、Button、Input、Tab，应重点放大组件本身。

完整页面主题：

例如 Landing Page、Dashboard，则可以展示较完整的页面。

---

# 十一、美术风格必须真正改变

每种风格需要从多个维度同步改变。

包括：

### Typography

- Serif
- Sans-serif
- Mono
- Display
- 字重
- 字距
- 字号
- 大小写
- 排版结构

### Color

- 主色
- 强调色
- 色彩数量
- 明暗
- 饱和度
- 对比关系

### Shape

- Sharp
- Rounded
- Pill
- Geometric
- Organic
- Irregular

### Border

- Hairline
- Thick Outline
- Double Border
- Pixel Border
- Decorative Border
- No Border

### Shadow

- No Shadow
- Soft Shadow
- Hard Shadow
- Inner Shadow
- Glow
- Colored Shadow

### Material

- Flat
- Glass
- Metal
- Chrome
- Plastic
- Paper
- Clay
- Ceramic
- Fabric
- CRT

### Graphic Language

- Geometry
- Pattern
- Sticker
- Doodle
- Pixel
- Collage
- Noise
- Grain
- Halftone

### Density

- 极简留白
- 高密度
- 层叠
- 强二维构成
- 强空间纵深

不能只换颜色。

---

# 十二、50 种风格必须提前规划

在开始生成图片前，执行 Agent 应先在内部规划完整：

**50 个不重复的美术风格。**

然后分配成：

```text
第 01 页：风格 01–05
第 02 页：风格 06–10
第 03 页：风格 11–15
第 04 页：风格 16–20
第 05 页：风格 21–25
第 06 页：风格 26–30
第 07 页：风格 31–35
第 08 页：风格 36–40
第 09 页：风格 41–45
第 10 页：风格 46–50
```

不能生成一页再临时想下一页。

否则容易出现：

- 重复
- 同义风格
- 后半部分没有可用风格
- 不同名称但视觉高度相似

---

# 十三、风格池

执行 Agent 可以从以下视觉谱系中自主挑选适合当前主体的风格。

这只是候选库，不是固定顺序。

### 现代 / 理性

- Minimalism
- Swiss Style
- International Style
- Functionalism
- Grid Modernism
- Corporate Modern

### 编辑 / 文化

- Editorial
- Newspaper
- Fashion Editorial
- Art Book
- Typography-led
- Monochrome Editorial

### 粗犷 / 实验

- Brutalism
- Neo-Brutalism
- Maximalism
- Anti-design
- Deconstruction
- Experimental Typography

### 科技 / 未来

- Dark Tech
- Futurism
- Cyberpunk
- Retrofuturism
- Sci-Fi HUD
- Holographic

### 半透明 / 光影

- Glassmorphism
- Frosted Glass
- Aurora
- Gradient Mesh
- Layered Transparency

### 材质

- Skeuomorphism
- Neumorphism
- Claymorphism
- Metallic
- Chrome
- Paper Texture

### 复古

- Retro Web
- Y2K
- Web 1.0
- Windows 95
- Macintosh Classic
- Vaporwave
- Synthwave

### 艺术运动

- Bauhaus
- Memphis
- Constructivism
- Abstract Geometry
- Collage
- Pop Art
- Psychedelic
- Op Art

### 插画

- Hand-drawn
- Monoline
- Flat Illustration
- Isometric
- 3D Illustration
- Low-poly
- Comic
- Pixel Art

### 自然 / 生活

- Organic
- Eco
- Japandi
- Wabi-sabi
- Scandinavian
- Botanical

### 高端品牌

- Luxury Minimal
- Quiet Luxury
- Premium Editorial
- Black & Gold
- High Fashion
- Architectural Minimal

执行 Agent 根据具体主题选择最有表现力的 50 种。

---

# 十四、避免伪风格差异

不要把：

```text
Minimal
Modern Minimal
Clean Minimal
Soft Minimal
Simple Minimal
```

当成 5 个风格。

名称不同但视觉高度一致，仍然算重复。

应该追求明显跨度。

例如：

```text
Swiss
Neo-Brutalism
Y2K
Editorial
Glassmorphism
Pixel Art
Bauhaus
Cyberpunk
Wabi-sabi
Memphis
```

这种组合的视觉差异才足够明显。

---

# 十五、禁止 AI 默认风格污染

禁止所有案例最后都变成：

- 蓝紫渐变
- AI SaaS
- 白色卡片
- 大圆角
- Pill Button
- Bento Grid
- Soft Shadow
- Inter 风无衬线
- 深色科技背景

如果案例名称为 Brutalism，就真正表现粗野主义。

如果是 Y2K，就真正使用 Y2K 视觉语言。

如果是 Editorial，就真正采用编辑设计体系。

如果是 Retro Web，就真正表现早期互联网语言。

---

# 十六、功能保持基本可比

为了让用户比较：

**美术风格**

不同案例的基本功能语义应尽量保持接近。

例如 Navbar 可以反复使用类似：

```text
Logo
Products
Solutions
Resources
About
Get Started
```

Button 可以反复使用：

```text
Get Started
Explore
Continue
```

Input 可以使用：

```text
Email address
Search anything...
```

不要一个案例展示完全不同的功能，从而破坏横向比较。

---

# 十七、状态可以存在，但不能成为分类核心

组件可以适当展示：

```text
DEFAULT
HOVER
ACTIVE
FOCUS
OPEN
SELECTED
```

但这些状态属于某一种风格内部。

不能把：

```text
Hover
Focus
Loading
Disabled
Active
```

当成五种美术风格。

---

# 十八、质量检查

生成每一页之前检查：

```text
当前页码是多少？
是否与上一页不同？
是否严格连续？
```

例如：

生成第 7 张时：

标题必须明确写：

```text
XXXX美术风格参考 07
```

不能写：

```text
XXXX美术风格参考 01
```

即使这是一次新的图片生成调用，也不能把序号重置。

---

# 十九、最终执行

严格执行：

```text
Generation 01 → 页面 01 → n=1
Generation 02 → 页面 02 → n=1
Generation 03 → 页面 03 → n=1
Generation 04 → 页面 04 → n=1
Generation 05 → 页面 05 → n=1
Generation 06 → 页面 06 → n=1
Generation 07 → 页面 07 → n=1
Generation 08 → 页面 08 → n=1
Generation 09 → 页面 09 → n=1
Generation 10 → 页面 10 → n=1
```

生成下一张时：

**继续系列编号。**

绝不重新从 01 开始。

最终得到：

**10 张独立图片 × 每张 5 个案例 = 50 个不同美术风格。**

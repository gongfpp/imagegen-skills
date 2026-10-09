# 通用设计功能分类参考图鉴生成 Prompt

生成一套围绕指定设计主体的 **「功能与结构分类参考图鉴」**。

共生成：

**10 张彼此完全独立的图片。**

每张图片包含：

**5 个不同功能 / 结构 / 交互案例。**

总计：

**10 张图片 × 5 个案例 = 50 个案例。**

本 Prompt 关注的是：

> **同一种设计主体，有哪些不同的功能类型、结构方式、交互模式和使用场景。**

本 Prompt 不以美术风格作为主要分类标准。

---

# 一、核心任务

执行 Agent 根据用户指定的设计主体，整理出尽可能完整、具有实际设计价值的：

- 功能类型
- 结构类型
- 信息组织方式
- 交互模式
- 状态模式
- 展开方式
- 定位方式
- 使用场景
- 内容类型
- 行为模式

例如主题是 Navbar，可以研究：

- Standard Header
- Centered Navigation
- Two-tier Header
- Mega Menu
- Sidebar Navigation
- Floating Navbar
- Sticky Navbar
- Scroll-aware Navbar
- Fullscreen Menu
- Off-canvas Navigation
- Search-first Navigation
- Breadcrumb Navigation
- Contextual Navigation
- Anchor Navigation
- Responsive Navigation

这里的核心问题是：

> **Navbar 到底有哪些设计类型？**

而不是：

> Navbar 可以做成多少种美术风格？

---

# 二、功能分类优先

不同案例之间的主要区别必须来自：

**结构、功能或交互机制。**

例如主题为 Button，可以按照：

- Primary Button
- Secondary Button
- Icon Button
- Split Button
- Dropdown Button
- Toggle Button
- Floating Action Button
- Loading Button
- Progress Button
- Hold-to-confirm Button
- Drag-to-confirm Button

分类。

主题为 Input，可以按照：

- Text Input
- Search Input
- Password Input
- Number Input
- Tag Input
- Autocomplete
- Token Input
- Inline Edit
- OTP Input
- Command Input

分类。

主题为 Landing Page，则可以按照：

- SaaS Landing Page
- Product Launch Page
- App Download Page
- Waitlist Page
- Lead Generation Page
- Pricing-first Page
- Demo-first Page
- Case-study-led Page
- Community Landing Page
- Game Landing Page

分类。

---

# 三、避免把美术风格当成功能分类

以下内容：

```text
Minimalism
Glassmorphism
Brutalism
Y2K
Cyberpunk
Bauhaus
Editorial
```

属于：

**美术风格。**

不属于本 Prompt 的主要分类依据。

可以给不同案例做适度视觉变化，提高图鉴丰富度，但不能把它们作为案例名称和核心区别。

本图鉴的案例名称应主要回答：

> **它是什么类型？**

> **它解决什么问题？**

> **它如何工作？**

---

# 四、输出数量

必须输出：

**10 张独立图片文件。**

每张：

**3:4 竖版。**

每张：

**5 个案例。**

总计：

**50 个功能 / 结构 / 交互案例。**

---

# 五、极其重要：禁止拼图

禁止：

- 十页拼成一张
- 5×2 拼图
- Contact Sheet
- 一张超长图
- 总览图代替独立图片
- 先生成大图再裁切

必须执行：

**10 次完全独立的图片生成。**

每次：

```text
n = 1
```

每次只生成：

**当前一个页面。**

---

# 六、页码规则——必须严格连续

顶部标题必须分别为：

```text
[主题名称]分类参考 01
[主题名称]分类参考 02
[主题名称]分类参考 03
[主题名称]分类参考 04
[主题名称]分类参考 05
[主题名称]分类参考 06
[主题名称]分类参考 07
[主题名称]分类参考 08
[主题名称]分类参考 09
[主题名称]分类参考 10
```

### 禁止

每次图片生成都写：

```text
[主题名称]分类参考 01
```

10 张图片的标题页码必须分别为：

```text
01
02
03
04
05
06
07
08
09
10
```

每个页码只使用一次。

---

# 七、页面编号与案例编号分离

顶部的：

```text
分类参考 07
```

表示：

**整个系列的第 7 页。**

页面内部的：

```text
01
02
03
04
05
```

表示：

**这一页内部的 5 个案例编号。**

两者不能混淆。

第 7 页正确结构：

```text
顶部：
XXXX分类参考 07

内部：
01
02
03
04
05
```

不要因为内部案例从 01 开始，就把顶部页码也变回 01。

---

# 八、50 个案例提前规划

开始生成前，执行 Agent 应先完整规划：

**50 个不重复的功能 / 结构 / 交互分类。**

然后分配：

```text
Page 01 → Case 01–05
Page 02 → Case 06–10
Page 03 → Case 11–15
Page 04 → Case 16–20
Page 05 → Case 21–25
Page 06 → Case 26–30
Page 07 → Case 31–35
Page 08 → Case 36–40
Page 09 → Case 41–45
Page 10 → Case 46–50
```

如果当前设计主体确实不存在 50 个合理的大分类，可以继续向下细分：

- 一级结构
- 二级结构
- 使用场景
- 行为方式
- 展开方式
- 状态机制

但不得为了凑数制造没有实际意义的名称。

---

# 九、外层统一版式

10 张图片使用完全相同的图鉴母版。

画面：

**3:4 竖版。**

背景：

**浅暖灰白。**

整体气质：

- Design Reference Book
- UI Pattern Library
- Component Reference Guide
- Interaction Pattern Handbook

外层统一：

- 标题
- 页边距
- 左右分栏
- 编号
- 字体层级
- 案例高度
- 分隔线
- 演示区尺寸

---

# 十、页面顶部

左上：

```text
[主题名称]分类参考 XX
```

其中：

```text
XX = 当前页码
```

英文副标题：

```text
DESIGN PATTERN REFERENCE
```

或：

```text
UI PATTERN REFERENCE
```

右上可以加入：

```text
结构
功能
交互

STRUCTURE
FUNCTION
INTERACTION
```

---

# 十一、每页 5 个案例

标题下方固定排列：

**5 个横向案例。**

每一个采用：

> 左侧说明 + 右侧实际演示

---

# 十二、左侧说明区

约占：

**25%–28%。**

包含：

```text
01

英文分类名称
中文分类名称

STRUCTURE
FUNCTION
BEHAVIOR
USE CASE

结构关键词
功能关键词
交互关键词
```

左侧主要回答：

> 这个类型叫什么？

> 它有什么特点？

---

# 十三、右侧演示区

约占：

**72%–75%。**

展示：

**这个类型实际长什么样、如何使用。**

如果主题是 Navbar：

展示 Navbar 与必要的页面环境。

如果是 Button：

展示按钮本身和必要交互状态。

如果是 Dropdown：

展示展开前与展开后。

如果是 Landing Page：

展示对应类型的首屏和核心页面结构。

如果是 Modal：

展示 Modal 与原页面之间的关系。

---

# 十四、允许展示多个状态

功能 / 交互类案例经常需要状态对比。

允许展示：

```text
DEFAULT
HOVER
OPEN
ACTIVE
LOADING
SUCCESS
ERROR
COLLAPSED
EXPANDED
```

如果状态变化正是这种功能分类的核心，应明确表现。

例如：

Accordion：

```text
COLLAPSED → EXPANDED
```

Dropdown：

```text
CLOSED → OPEN
```

Search Autocomplete：

```text
EMPTY → TYPING → RESULTS
```

---

# 十五、结构差异要真正明显

不要只是：

```text
Standard Navbar
Modern Navbar
Simple Navbar
Clean Navbar
```

这些名称并没有明确结构区别。

更好的分类应该类似：

```text
Standard Horizontal Header
Centered Header
Two-tier Navigation
Mega Menu
Vertical Sidebar
Floating Navigation
Fullscreen Menu
Off-canvas Drawer
Search-first Navigation
Anchor Navigation
```

每一种必须存在：

**实际结构或功能差异。**

---

# 十六、避免功能重复

名称不同但工作方式相同，也视为重复。

例如：

```text
Sticky Navbar
Fixed Navbar
Pinned Navbar
```

如果三者实际上完全相同，不应占三个案例。

应该优先追求：

**不同设计模式。**

---

# 十七、美术风格保持辅助地位

不同案例可以适当采用不同视觉设计，使图鉴更容易阅读。

但不要出现：

```text
Brutalist Navbar
Glass Navbar
Y2K Navbar
```

这种纯视觉风格名称。

除非这种视觉语言本身直接产生了不同的结构或交互，否则不属于本 Prompt 的分类核心。

---

# 十八、信息密度

右侧 Demo 应足够大。

不要为了表示“这是一个网站”而把完整网页缩得很小。

局部组件：

**优先放大组件。**

完整页面：

**展示核心结构。**

功能关系：

**优先展示状态变化和结构关系。**

---

# 十九、文字原则

案例名称应尽量采用行业中真实存在、可以理解和检索的模式名称。

避免自行发明：

```text
Super Smart Navigation
Future Navigation
Ultra Menu
Amazing Header
```

这类没有设计分类意义的名称。

---

# 二十、质量检查

生成每一页前检查：

### 页码

```text
当前页面应该是几？
```

例如当前是第 9 页：

必须使用：

```text
XXXX分类参考 09
```

不能再次写：

```text
XXXX分类参考 01
```

### 案例

检查：

- 是否与前 8 页重复
- 是否只是换名字
- 是否有真正功能区别
- 是否属于当前设计主体
- 是否仍有实际参考价值

---

# 二十一、最终执行

严格按照：

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

生成下一张图片时：

**页码继续递增。**

绝对不能因为重新调用图片生成工具就重新变成 01。

最终得到：

**10 张独立图片 × 每张 5 个案例 = 50 个不同功能 / 结构 / 交互类型。**

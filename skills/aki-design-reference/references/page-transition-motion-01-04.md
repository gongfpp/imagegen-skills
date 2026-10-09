# 页面转场与 Motion Design 风格参考图鉴生成 Prompt

生成一组「页面转场与 Motion Design 风格参考图鉴」，共生成 **4 张彼此独立的竖版长图**，每张图片包含 **5 种不同的页面转场、页面切换与界面 Motion Design 方案**，共 20 种。

## 重要输出要求

必须输出 **4 张彼此独立的图片文件**。

每张图片都是一张完整的 **3:4 竖版设计图**。

禁止把 4 张图片拼接到同一张超长图、四宫格、2×2 拼图、Contact Sheet、总览图或单一画布中。

禁止让我后期手动裁切。

我要直接得到：

- 第 1 张：页面转场与 Motion Design 风格参考 01
- 第 2 张：页面转场与 Motion Design 风格参考 02
- 第 3 张：页面转场与 Motion Design 风格参考 03
- 第 4 张：页面转场与 Motion Design 风格参考 04

每张独立图片内部包含 5 个纵向排列的页面转场与 Motion Design 案例。

---

# 整体定位

这是一套面向：

- UI/UX Designer
- Front-end Developer
- Motion Designer
- Interaction Designer
- Web Designer
- App Designer

的高质量：

**PAGE TRANSITION & MOTION DESIGN REFERENCE**

用于直观展示不同网页 / App 页面在：

- 页面进入
- 页面离开
- 路由切换
- 内容替换
- 页面展开
- 模态层切换
- 页面滚动
- Scene Transition
- View Transition
- Shared Element Transition

等场景下的运动方式。

这不是普通的静态网页风格合集。

重点必须表现：

**页面 A 如何运动、拆解、遮挡、缩放、切换或变形成页面 B。**

最终图片虽然是静态设计图，但必须通过：

**关键帧序列 + 运动轨迹 + 中间状态 + 页面 A / 页面 B 对照**

让观看者一眼理解完整转场过程。

整体视觉类似：

- UI/UX Motion Design Reference Book
- Interaction Design Handbook
- Web Motion Design Guide
- App Transition Design Manual
- Figma / Framer / Rive / GSAP Motion Showcase
- 高级设计杂志中的 Motion Design 分析页
- Professional Page Transition Reference

---

# 整体版式

4 张图片必须严格采用同一套设计系统。

画面比例：

**3:4 竖版长图**

高清。

背景：

**非常浅的暖灰白色。**

整体干净、高级、克制。

顶部保留统一大标题区域。

标题分别为：

```text
页面转场与 Motion Design 风格参考 01
页面转场与 Motion Design 风格参考 02
页面转场与 Motion Design 风格参考 03
页面转场与 Motion Design 风格参考 04
```

标题下方加入英文：

```text
PAGE TRANSITION & MOTION DESIGN REFERENCE
```

右上角加入极小辅助文字，例如：

```text
探索空间与时间
构建自然的界面连续性

TRANSITION
MOTION
CONTINUITY
```

辅助文字不要抢夺主标题视觉权重。

---

# 每张图片内部布局

每张图片划分成 **5 个横向案例区域**。

从上到下纵向排列。

每个案例采用完全统一的结构。

---

# 左侧信息区

左侧约占整体宽度的 25%–28%。

包含：

- 编号
- 英文转场名称
- 中文转场名称
- 3–4 个英文关键词
- 2–4 个中文关键词

例如：

```text
01

Slide Transition
滑动转场

SLIDE
DIRECTION
CONTINUITY
SPATIAL

方向
连续
空间
页面切换
```

---

# 右侧 Motion Demo 区

右侧约占整体宽度的 72%–75%。

展示：

**页面 A → 转场过程 → 页面 B**

每种案例建议展示 **3–5 个关键帧**。

例如：

```text
PAGE A
→ TRANSITION 01
→ TRANSITION 02
→ PAGE B
```

或者：

```text
CURRENT VIEW
→ EXIT
→ OVERLAP
→ ENTER
→ NEW VIEW
```

每一帧都应使用真实的 Desktop Web / App 页面 Mockup。

必须能够看到：

- Header
- Navigation
- Hero
- Cards
- Text
- Image
- Content
- Modal
- Panel
- Page Structure

等真实界面元素。

不能只画几个抽象方块来代替页面。

---

# 静态图片如何表达 Motion

必须通过以下方式表现运动：

- Motion Arrow
- Motion Path
- Ghost Frame
- Motion Blur
- Position Trail
- Scale Difference
- Rotation Difference
- Opacity Difference
- Mask
- Clip Path
- Layer Overlap
- Perspective
- Depth
- Blur
- Transform Origin
- Shared Element
- Cursor / Scroll Indicator
- Timeline

必须能够一眼看出：

```text
哪个页面离开
↓
向什么方向运动
↓
哪个元素先动
↓
中间如何过渡
↓
新页面如何出现
```

---

# Motion Spec

每种案例右下方可以加入非常小的参数标注：

```text
Duration   600ms
Exit       240ms
Enter      420ms
Ease       cubic-bezier(.22,.8,.2,1)
```

也可以标注：

```text
Transform
X   0 → -100%
Opacity   1 → 0
```

或者：

```text
Scale
1.00 → 0.92 → 1.00
```

参数作为设计教材式辅助信息存在。

不要抢占主要视觉空间。

---

# 第 01 张图片

## 标题

```text
页面转场与 Motion Design 风格参考 01
PAGE TRANSITION & MOTION DESIGN REFERENCE
```

---

## 01 — Horizontal Slide / 水平滑动转场

关键词：

```text
SLIDE
HORIZONTAL
DIRECTION
CONTINUITY
```

中文关键词：

```text
横向滑动
空间连续
方向感
页面切换
```

### 动效逻辑

当前页面 Page A 向左移动。

新页面 Page B 从右侧进入。

两张页面在转场过程中短暂同时存在。

形成明显的空间连续关系。

### 关键帧

```text
PAGE A
→ A -30% / B ENTER
→ A -70% / B 70%
→ PAGE B
```

必须明确展示两个页面相对位移。

可以加入水平 Motion Arrow。

### 视觉感受

自然、直接、符合空间模型。

适合：

- Carousel Page
- 多步骤流程
- Dashboard
- Mobile Navigation
- 页面层级切换

---

## 02 — Vertical Slide / 垂直滑动转场

关键词：

```text
VERTICAL
SLIDE
STACK
FLOW
```

中文关键词：

```text
上下切换
垂直空间
堆叠
流程感
```

### 动效逻辑

Page A 向上离开。

Page B 从底部进入。

或者反向操作。

### 关键帧

```text
PAGE A
→ A UP / B ENTER
→ OVERLAP
→ PAGE B
```

页面之间保持相同布局尺寸。

通过上下方向建立“内容向下一层推进”的感觉。

适合：

- 全屏官网
- Story 页面
- Section Navigation
- Mobile App

---

## 03 — Fade Through / 淡入淡出转场

关键词：

```text
FADE
OPACITY
SOFT
SUBTLE
```

中文关键词：

```text
淡出
淡入
柔和
低干扰
```

### 动效逻辑

Page A 的：

```text
Opacity
1 → 0
```

同时 Page B：

```text
Opacity
0 → 1
```

但不要简单交叉淡化。

中间可以加入极轻微：

```text
Scale 1 → 0.98
Blur 0 → 6px
```

形成更自然的层次。

### 关键帧

```text
PAGE A
→ FADE OUT
→ NEUTRAL MIDPOINT
→ FADE IN
→ PAGE B
```

### 适用

- 内容切换
- Modal
- Tab
- Portfolio
- Minimal Website

---

## 04 — Scale Zoom / 缩放转场

关键词：

```text
ZOOM
SCALE
DEPTH
FOCUS
```

中文关键词：

```text
缩放
纵深
聚焦
空间
```

### 动效逻辑

点击当前页面中的某个内容卡片。

卡片逐渐放大。

最终卡片成为下一页面的完整内容区域。

Page A 的其他元素同步淡出。

### 关键帧

```text
PAGE A
→ CARD SELECT
→ CARD SCALE 160%
→ CARD FULLSCREEN
→ DETAIL PAGE
```

重点表现：

**点击对象本身成为下一页。**

适合：

- Gallery
- Portfolio
- 商品详情
- 新闻详情
- 图片网站

---

## 05 — Push Transition / 推入转场

关键词：

```text
PUSH
LAYER
DIRECTION
SPATIAL
```

中文关键词：

```text
推入
层级
位移
空间关系
```

### 动效逻辑

Page B 从右侧快速进入。

并直接把 Page A 向左推走。

区别于普通 Slide：

新页面具有明显主动“推”的感觉。

### 关键帧

```text
A FULL
→ B PUSH 25%
→ B PUSH 60%
→ A EXIT
→ B FULL
```

两张页面的边界必须始终明显。

---

# 第 02 张图片

## 标题

```text
页面转场与 Motion Design 风格参考 02
PAGE TRANSITION & MOTION DESIGN REFERENCE
```

---

## 01 — Wipe Reveal / 擦除揭示

关键词：

```text
WIPE
MASK
REVEAL
DIRECTION
```

中文关键词：

```text
擦除
遮罩
揭示
方向
```

### 动效逻辑

Page B 已经位于底层。

Page A 通过一块 Mask 从左向右逐渐被擦除。

底层新页面随之显现。

### 关键帧

```text
PAGE A
→ 25% WIPE
→ 50% WIPE
→ 80% WIPE
→ PAGE B
```

必须明确显示 Mask Edge。

边缘可以是：

- Straight Line
- Soft Gradient
- Angled Line

整体保持高级、克制。

---

## 02 — Curtain Split / 幕布分裂

关键词：

```text
SPLIT
CURTAIN
REVEAL
CENTER
```

中文关键词：

```text
分裂
幕布
中心展开
舞台感
```

### 动效逻辑

Page A 从中央分为左右两个部分。

左侧向左离开。

右侧向右离开。

Page B 从中间逐渐显现。

### 关键帧

```text
CLOSED
→ CENTER SPLIT
→ HALF OPEN
→ FULL OPEN
→ PAGE B
```

类似舞台幕布。

适合：

- Creative Portfolio
- Fashion
- Film
- Luxury
- Brand Website

---

## 03 — Diagonal Wipe / 对角线擦除

关键词：

```text
DIAGONAL
MASK
DYNAMIC
GRAPHIC
```

中文关键词：

```text
斜切
遮罩
动态图形
冲击
```

### 动效逻辑

大型斜线 Mask 从左下向右上移动。

Page A 被逐渐覆盖。

Page B 随后显现。

### 关键帧

```text
PAGE A
→ DIAGONAL ENTER
→ 50% COVER
→ 80% COVER
→ PAGE B
```

构图应有很强的平面 Graphic Design 感。

适合：

- Sports
- Fashion
- Creative Agency
- Event
- 游戏官网

---

## 04 — Color Block Transition / 色块覆盖

关键词：

```text
COLOR
BLOCK
COVER
BRAND
```

中文关键词：

```text
色块
覆盖
品牌
节奏
```

### 动效逻辑

一个或多个品牌色块从页面边缘快速进入。

完全覆盖 Page A。

在画面全色状态时切换页面。

色块随后离开。

露出 Page B。

### 关键帧

```text
PAGE A
→ COLOR BLOCK ENTER
→ FULL COLOR
→ BLOCK EXIT
→ PAGE B
```

可以使用：

- Single Brand Color
- Two Color Layers
- Three Sequential Blocks

但不要过于花哨。

---

## 05 — Shape Mask / 几何遮罩转场

关键词：

```text
SHAPE
MASK
GEOMETRY
EXPAND
```

中文关键词：

```text
几何
遮罩
扩张
图形
```

### 动效逻辑

一个圆形或几何图形从点击位置产生。

不断扩大。

最终覆盖整个屏幕。

在覆盖过程中显示 Page B。

### 关键帧

```text
SMALL SHAPE
→ MEDIUM
→ LARGE
→ FULLSCREEN
→ PAGE B
```

图形可以使用：

- Circle
- Rounded Rectangle
- Hexagon

重点是 Mask Expansion。

---

# 第 03 张图片

## 标题

```text
页面转场与 Motion Design 风格参考 03
PAGE TRANSITION & MOTION DESIGN REFERENCE
```

---

## 01 — Shared Element / 共享元素转场

关键词：

```text
SHARED
ELEMENT
CONTINUITY
MORPH
```

中文关键词：

```text
共享元素
连续性
元素接续
形变
```

### 动效逻辑

Page A 中存在一个图片卡片。

点击后：

图片保持为同一个视觉对象。

从卡片尺寸移动并放大到 Page B 顶部 Hero。

其他页面元素才随后出现。

### 关键帧

```text
CARD
→ MOVING CARD
→ LARGE IMAGE
→ HERO IMAGE
→ DETAIL PAGE
```

必须强调：

**这个图片不是消失后重新出现，而是连续移动过去。**

---

## 02 — Layout Morph / 布局形变

关键词：

```text
LAYOUT
MORPH
REFLOW
CONTINUITY
```

中文关键词：

```text
布局形变
重排
连续
结构变化
```

### 动效逻辑

Page A 是 Card Grid。

切换到 Page B 后：

卡片不是重新加载。

而是在画面中逐渐移动和重新排列。

例如：

```text
3 COLUMN GRID
→ MOVING CARDS
→ 2 COLUMN
→ LIST
```

### 关键帧

展示同一组 UI 元素重新组织布局。

适合：

- Filter
- Sort
- View Switch
- Dashboard
- Gallery

---

## 03 — Card to Page / 卡片展开为页面

关键词：

```text
CARD
EXPAND
DETAIL
MORPH
```

中文关键词：

```text
卡片展开
详情页
形变
连续
```

### 动效逻辑

用户点击卡片。

卡片：

- Width 增大
- Height 增大
- Border Radius 减少
- 图片扩大
- 标题重新定位

最终卡片自身成为全屏详情页。

### 关键帧

```text
CARD
→ EXPAND
→ LARGE PANEL
→ FULLSCREEN
→ DETAIL
```

---

## 04 — Thumbnail to Hero / 缩略图放大

关键词：

```text
IMAGE
ZOOM
HERO
SHARED
```

中文关键词：

```text
缩略图
放大
主视觉
连续图片
```

### 动效逻辑

Gallery 中的小图被点击。

图片沿页面 Z 轴向前放大。

同时移动至 Hero 区域。

背景页面逐渐淡出。

### 关键帧

```text
THUMBNAIL
→ IMAGE LIFT
→ IMAGE SCALE
→ HERO POSITION
→ DETAIL VIEW
```

突出图片空间连续性。

---

## 05 — Modal Morph / 模态框形变

关键词：

```text
MODAL
MORPH
EXPAND
LAYER
```

中文关键词：

```text
弹窗
展开
层级
形变
```

### 动效逻辑

用户点击一个小按钮或卡片。

一个小型 Popover / Modal 出现。

随后继续扩大。

最终成为完整页面。

### 关键帧

```text
BUTTON
→ POPOVER
→ MODAL
→ LARGE PANEL
→ FULL PAGE
```

展示从局部 UI 到完整页面的连续过渡。

---

# 第 04 张图片

## 标题

```text
页面转场与 Motion Design 风格参考 04
PAGE TRANSITION & MOTION DESIGN REFERENCE
```

---

## 01 — Parallax Transition / 视差转场

关键词：

```text
PARALLAX
DEPTH
LAYER
SCROLL
```

中文关键词：

```text
视差
纵深
多层
滚动
```

### 动效逻辑

页面包含：

- Foreground
- Content
- Background

三层。

转场时三层以不同速度移动。

例如：

```text
FOREGROUND 100%
CONTENT     70%
BACKGROUND  30%
```

形成明显空间纵深。

### 静态表达

展示多个图层的 Motion Arrow。

箭头长度不同。

必须一眼看出层与层速度不同。

---

## 02 — Perspective Flip / 透视翻页

关键词：

```text
3D
PERSPECTIVE
FLIP
ROTATE
```

中文关键词：

```text
透视
翻转
3D
页面旋转
```

### 动效逻辑

整个页面像一张大型卡片。

沿 Y 轴进行 3D Rotation。

```text
0°
→ 45°
→ 90°
→ 135°
→ 180°
```

另一侧成为 Page B。

需要明显展示 Perspective。

### 适合

- Experimental Website
- Portfolio
- 游戏
- Creative Studio

不要做成廉价 PowerPoint 翻页特效。

整体应保持高级网页 Motion Design 感。

---

## 03 — Depth Stack / 景深堆叠转场

关键词：

```text
DEPTH
STACK
BLUR
LAYER
```

中文关键词：

```text
层叠
景深
模糊
空间
```

### 动效逻辑

当前 Page A 缩小并向后退。

同时 Blur 增加。

Page B 从前景进入。

形成多个页面堆叠在 Z 轴上的空间模型。

### 关键帧

```text
A FRONT
→ A BACK
→ B ENTER
→ DEPTH OVERLAP
→ B FRONT
```

可以显示背景页面残留边缘。

形成空间层级。

---

## 04 — Blur Transition / 模糊转场

关键词：

```text
BLUR
FOCUS
SOFT
CINEMATIC
```

中文关键词：

```text
模糊
聚焦
柔和
电影感
```

### 动效逻辑

Page A：

```text
Blur
0 → 12px
```

同时：

```text
Opacity
1 → 0
```

Page B：

```text
Blur
12px → 0
Opacity
0 → 1
```

形成镜头重新对焦的感觉。

### 关键帧

```text
A SHARP
→ A BLUR
→ FULL BLUR
→ B BLUR
→ B SHARP
```

适合：

- Luxury
- Film
- Portfolio
- Photography
- Minimal UI

---

## 05 — Scrollytelling Scene / 滚动叙事转场

关键词：

```text
SCROLL
STORY
SCENE
TIMELINE
```

中文关键词：

```text
滚动
叙事
场景
时间轴
```

### 动效逻辑

用户向下滚动。

页面不是直接垂直离开。

而是通过 Scroll Progress 驱动多个元素：

```text
0%
25%
50%
75%
100%
```

进行：

- Scale
- Position
- Opacity
- Camera Movement
- Text Reveal
- Image Change

最终进入下一 Scene。

### 静态图展示

显示：

```text
SCENE 01
↓
25%
↓
50%
↓
75%
↓
SCENE 02
```

配合侧边 Scroll Progress Bar。

突出滚动与动画进度绑定。

---

# 四张图片统一质量控制

4 张图片必须看起来像同一本：

**PAGE TRANSITION & MOTION DESIGN REFERENCE**

中的连续第 01–04 页。

必须统一：

- 3:4 画面比例
- 暖灰白背景
- 顶部标题
- 英文副标题
- 左侧编号系统
- 左侧信息栏宽度
- 右侧 Motion Demo 区宽度
- 每个案例高度
- 页边距
- 字体体系
- 分隔线
- 圆角
- Motion Spec
- 关键帧标注系统
- 页面 Mockup 样式

每张图严格包含 5 个案例。

统一的是：

**图鉴本身的 Editorial Design System。**

不同的是：

**每种页面转场自身的 Motion Language。**

---

# 页面 Demo 要求

每个案例中用于演示的 Page A 与 Page B 都必须像真正设计完成的网页或 App 页面。

不要用纯色矩形代替页面。

应包含：

- Navigation
- Logo
- Hero
- Text
- Image
- Card
- Button
- Sidebar
- Gallery
- Product
- Dashboard

等真实界面结构。

但界面内容应保持克制。

重点始终是：

**Motion。**

不是网页内容本身。

---

# 避免错误

不要把 20 个案例做成普通网页 UI 风格对比。

不要仅仅换不同网页颜色。

不要只画：

```text
PAGE A
PAGE B
```

而完全没有中间过程。

不要所有转场都只是：

```text
Fade
Slide
Scale
```

的轻微变体。

每一种案例必须有明确不同的核心运动机制。

不要所有页面都使用：

- 蓝紫渐变
- 大圆角
- Glassmorphism
- SaaS Dashboard

不同案例中的网页本身可以使用不同视觉风格，以便体现转场特性。

但外围图鉴排版必须完全一致。

---

# 最重要的表达规则

每种案例都必须回答以下问题：

```text
转场从什么状态开始？
↓
什么元素先运动？
↓
运动方向是什么？
↓
页面之间是否同时存在？
↓
中间发生什么？
↓
什么元素保持连续？
↓
最终新页面如何稳定下来？
```

至少展示 3 个关键帧。

推荐 4–5 个。

例如：

```text
PAGE A
→ EXIT
→ OVERLAP
→ ENTER
→ PAGE B
```

复杂 Shared Element 类：

```text
PAGE A
→ ELEMENT SELECT
→ ELEMENT MOVE
→ LAYOUT MORPH
→ PAGE B
```

---

# 最终输出规则

最终必须生成 **4 张独立图片文件**：

```text
Image 1 = 页面转场与 Motion Design 风格参考 01
Image 2 = 页面转场与 Motion Design 风格参考 02
Image 3 = 页面转场与 Motion Design 风格参考 03
Image 4 = 页面转场与 Motion Design 风格参考 04
```

每张：

```text
3:4 竖版
5 个案例
一个完整页面
独立构图
```

再次强调：

**禁止把 4 页放入同一张图。**

**禁止四宫格。**

**禁止 2×2 拼图。**

**禁止 Contact Sheet。**

**禁止输出一张需要后期裁切的超大图片。**

必须分别进行 4 次独立生成。

```text
第一次：只生成「页面转场与 Motion Design 风格参考 01」
第二次：只生成「页面转场与 Motion Design 风格参考 02」
第三次：只生成「页面转场与 Motion Design 风格参考 03」
第四次：只生成「页面转场与 Motion Design 风格参考 04」
```

每次：

```text
n = 1
```

不要一次生成包含 4 页的综合图片。

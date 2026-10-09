# 前端按钮动效风格参考图鉴生成 Prompt

生成一组「前端按钮动效设计风格参考图鉴」，共生成 **4 张彼此独立的竖版长图**，每张图片包含 **5 种不同的按钮交互与动效设计风格**，共 20 种。

## 重要输出要求

必须输出 **4 张彼此独立的图片文件**。

每张图片都是一张完整的 **3:4 竖版设计图**。

禁止把 4 张图片拼接到同一张超长图、四宫格、2×2 拼图、联系表、总览图或单一画布中。

禁止让我后期手动裁切。

我要直接得到：

- 第 1 张：前端按钮动效风格参考 01
- 第 2 张：前端按钮动效风格参考 02
- 第 3 张：前端按钮动效风格参考 03
- 第 4 张：前端按钮动效风格参考 04

每张独立图片内部包含 5 个纵向排列的按钮动效设计案例。

---

# 整体定位

这是一套面向：

- UI/UX 设计师
- 前端开发者
- Web Designer
- Motion Designer
- Interaction Designer

的高质量：

**Button Motion Design Reference**

用于直观展示不同按钮在：

- Default
- Hover
- Focus
- Press
- Click
- Loading
- Success
- Error
- Disabled

等状态下的视觉变化与动画语言。

这不是普通的「按钮 UI 样式合集」。

重点必须放在：

**按钮如何动、如何反馈、如何从一个状态过渡到另一个状态。**

整体视觉类似：

- 高质量 UI/UX Design Reference Book
- Motion Design 教材
- 前端交互动效设计手册
- 高级设计杂志中的组件分析页
- Figma / Framer / Rive / Web Motion Design Showcase
- Professional Interaction Design System

---

# 整体版式

4 张图片必须严格采用同一套设计系统。

画面比例：

**3:4 竖版长图**

高清。

背景使用：

**非常浅的暖灰白色**

整体干净、高级、克制。

顶部保留统一的大标题区域。

标题分别为：

```text
前端按钮动效风格参考 01
前端按钮动效风格参考 02
前端按钮动效风格参考 03
前端按钮动效风格参考 04
```

标题下方加入小号英文：

```text
BUTTON MOTION DESIGN REFERENCE
```

右上角可以加入极小的杂志式辅助文字，例如：

```text
探索交互细节
创造更自然的反馈体验

MOTION
INTERACTION
FEEDBACK
```

不要抢夺主标题视觉权重。

---

# 每张图片内部布局

每张图片划分成 **5 个横向案例区域**，从上到下纵向排列。

每个案例采用完全统一的结构。

## 左侧信息区

左侧约占整体宽度的 25%–28%。

包含：

- 编号，例如 01
- 英文动效名称
- 中文动效名称
- 3–4 个极短英文关键词
- 2–4 个极短中文关键词

例如：

```text
01

Fill Sweep
颜色扫入

HOVER
FILL
DIRECTION
SMOOTH

方向感
颜色填充
平滑反馈
```

---

# 右侧按钮动效演示区

右侧约占整体宽度的 72%–75%。

重点展示：

**同一个按钮从初始状态到交互结束的状态变化。**

每个案例建议展示 **3–5 个关键帧**。

例如：

```text
DEFAULT → HOVER → PRESS → ACTIVE
```

或者：

```text
IDLE → CLICK → LOADING → SUCCESS
```

多个关键帧沿水平方向排列。

帧与帧之间可使用：

- 极细箭头
- Motion Path
- 运动轨迹
- 残影
- 元素位移
- 形变中间态
- Scale 变化
- Glow 变化
- 边框扩散
- 粒子
- Progress
- Timing Curve

来表现动画过程。

因为最终输出为静态图片，因此必须通过：

**关键帧序列 + 运动轨迹 + 中间态**

让观看者能够一眼理解按钮究竟是如何运动的。

不能只展示几个几乎一样的静态按钮。

---

# 动效信息标注

每一个案例可以在右侧 Demo 下方加入极小的 Motion Spec。

例如：

```text
Hover      180ms
Press       90ms
Release    220ms
Ease       cubic-bezier(.2,.8,.2,1)
```

或者：

```text
Scale
1.00 → 1.04 → 0.96 → 1.00
```

也可以标注：

```text
Transform
Opacity
Blur
Stroke
Fill
Shadow
Spring
```

这些参数作为设计教材式辅助信息存在。

不要让它们抢占主要视觉空间。

---

# 第 01 张图片

## 标题

```text
前端按钮动效风格参考 01
BUTTON MOTION DESIGN REFERENCE
```

---

## 01 — Fill Sweep / 颜色扫入

关键词：

```text
HOVER
FILL
DIRECTION
SMOOTH
```

中文关键词：

```text
方向填充
颜色覆盖
平滑过渡
悬停反馈
```

### 动效逻辑

默认状态：

白色或透明按钮，黑色文字，细边框。

Hover 后：

一块强调色从按钮左侧向右快速滑入。

颜色逐渐覆盖整个按钮背景。

文字颜色同时由黑色变为白色。

### 关键帧展示

```text
DEFAULT → 30% FILL → 70% FILL → FULL HOVER
```

应明显展示颜色块从左向右运动的过程。

允许加入细小方向箭头。

### 视觉效果

克制、现代、清晰。

适合：

- SaaS
- Portfolio
- Landing Page
- 企业官网

---

## 02 — Border Draw / 描边绘制

关键词：

```text
STROKE
DRAW
OUTLINE
PRECISE
```

中文关键词：

```text
描边生长
路径动画
边框反馈
精确感
```

### 动效逻辑

默认：

只有文字或者非常淡的边框。

Hover 时：

按钮四周边框像 SVG Path 一样被逐段绘制出来。

可以从左上角开始：

```text
TOP → RIGHT → BOTTOM → LEFT
```

最终形成完整矩形或圆角矩形边框。

### 关键帧

```text
TEXT ONLY
→ TOP STROKE
→ HALF BORDER
→ COMPLETE BORDER
```

需要明显表现 Stroke 路径运动。

### 视觉效果

极简、理性、精密。

适合：

- 设计工作室
- 建筑网站
- 高端品牌
- Portfolio

---

## 03 — Magnetic Hover / 磁吸跟随

关键词：

```text
MAGNETIC
CURSOR
FOLLOW
ELASTIC
```

中文关键词：

```text
鼠标吸附
弹性位移
跟随反馈
空间感
```

### 动效逻辑

按钮会受到鼠标位置影响。

鼠标靠近按钮右侧时：

按钮主体轻微向右移动。

内部文字移动幅度略小。

鼠标离开后：

按钮通过 Spring 弹性动画回到原位。

### 静态画面表达

展示鼠标 Cursor 的多个位置。

使用轨迹线表现：

```text
CURSOR APPROACH
→ BUTTON SHIFT
→ MAX OFFSET
→ SPRING RETURN
```

按钮可以出现轻微拉伸和残影。

### 视觉效果

高级、顺滑、具有空间互动感。

适合：

- Awwwards 风格网站
- 创意工作室
- Portfolio
- 品牌官网

---

## 04 — Press Scale / 按压缩放

关键词：

```text
PRESS
SCALE
TACTILE
SPRING
```

中文关键词：

```text
缩放
按压反馈
弹性回弹
触觉感
```

### 动效逻辑

Hover：

按钮从 1.00 放大至 1.03。

Mouse Down：

迅速压缩至 0.94–0.96。

Release：

轻微超过原尺寸至 1.02。

随后回到 1.00。

### 关键帧

```text
1.00
→ 1.03
→ 0.95
→ 1.02
→ 1.00
```

按钮阴影同时发生变化：

```text
NORMAL SHADOW
→ DEEP SHADOW
→ FLAT
→ SOFT SHADOW
```

### 视觉效果

自然、可靠、具有真实触觉。

适合绝大多数现代 UI。

---

## 05 — Arrow Slide / 箭头滑入

关键词：

```text
ICON
SLIDE
DIRECTION
CTA
```

中文关键词：

```text
箭头进入
内容位移
方向反馈
行动提示
```

### 动效逻辑

默认：

按钮只显示：

```text
Explore
```

Hover：

文字略向左移动。

右侧箭头从按钮外部滑入。

最终：

```text
Explore   →
```

也可以表现旧箭头离开、新箭头进入的循环效果。

### 关键帧

```text
TEXT
→ TEXT SHIFT
→ ARROW ENTER
→ FINAL STATE
```

### 视觉效果

非常适合作为：

- Learn More
- Explore
- View Project
- Continue
- Next

类型 CTA。

---

# 第 02 张图片

## 标题

```text
前端按钮动效风格参考 02
BUTTON MOTION DESIGN REFERENCE
```

---

## 01 — Ripple Click / 涟漪点击

关键词：

```text
RIPPLE
CLICK
EXPAND
FEEDBACK
```

中文关键词：

```text
点击波纹
圆形扩散
即时反馈
触点反馈
```

### 动效逻辑

用户点击按钮的位置生成一个小圆。

圆形从点击位置迅速向四周扩大。

同时降低透明度。

最终完全消失。

### 关键帧

```text
CLICK POINT
→ SMALL RIPPLE
→ LARGE RIPPLE
→ FADE OUT
```

按钮本体保持稳定。

重点体现波纹扩散。

类似 Material Design 中经典 Ripple Interaction。

---

## 02 — Glow Pulse / 光晕脉冲

关键词：

```text
GLOW
PULSE
LIGHT
FOCUS
```

中文关键词：

```text
光晕
呼吸
聚焦
能量感
```

### 动效逻辑

Hover 后：

按钮外围出现柔和 Glow。

Glow 由弱变强。

随后轻微向外扩散。

可以形成一次或者持续的 Pulse。

### 关键帧

```text
NO GLOW
→ SOFT GLOW
→ PEAK GLOW
→ OUTER PULSE
```

### 视觉语言

深色背景。

蓝色、紫色、青色光晕。

适合：

- AI
- Web3
- Cyberpunk
- 科技产品
- Gaming UI

---

## 03 — Liquid Fill / 液体填充

关键词：

```text
LIQUID
FLUID
WAVE
FILL
```

中文关键词：

```text
液体
波浪
填充
流动
```

### 动效逻辑

Hover 或 Click 后：

彩色液体从按钮底部逐渐上涨。

液体顶部存在明显波浪曲线。

最终填满整个按钮。

### 关键帧

```text
EMPTY
→ 30%
→ 65%
→ 100%
```

中间态应明显呈现液体波浪变化。

### 视觉效果

有趣、流体化、年轻。

适合：

- 创意网站
- 娱乐产品
- 游戏
- 活动页面

---

## 04 — Split Reveal / 分裂展开

关键词：

```text
SPLIT
REVEAL
EXPAND
TRANSFORM
```

中文关键词：

```text
分裂
展开
揭示
形变
```

### 动效逻辑

按钮 Hover 后：

按钮背景沿中心向上下或者左右分裂。

两个色块分别向外运动。

底层新的颜色或文字被 Reveal。

例如：

```text
DOWNLOAD
```

Hover 后变成：

```text
START ↓
```

### 关键帧

```text
CLOSED
→ SPLIT
→ OPENING
→ REVEALED
```

突出遮罩与 Reveal 动画。

---

## 05 — Shadow Lift / 悬浮抬升

关键词：

```text
DEPTH
SHADOW
LIFT
HOVER
```

中文关键词：

```text
悬浮
阴影
层级
抬升
```

### 动效逻辑

默认：

按钮紧贴页面。

Hover：

按钮向上移动约 3–6 px。

阴影向下拉长。

Press：

按钮迅速落下。

阴影缩短。

### 关键帧

```text
REST
→ HOVER LIFT
→ MAX LIFT
→ PRESS DOWN
```

突出按钮的 Z-axis 空间变化。

---

# 第 03 张图片

## 标题

```text
前端按钮动效风格参考 03
BUTTON MOTION DESIGN REFERENCE
```

---

## 01 — Loading Morph / 加载形变

关键词：

```text
MORPH
LOADING
PROGRESS
STATE
```

中文关键词：

```text
形变
加载
状态切换
进度反馈
```

### 动效逻辑

默认按钮：

```text
SUBMIT
```

点击后：

按钮横向宽度快速收缩。

从长方形变成圆形。

文字淡出。

Spinner 出现。

### 关键帧

```text
SUBMIT
→ TEXT FADE
→ WIDTH SHRINK
→ CIRCLE
→ SPINNER
```

重点表现 Shape Morphing。

---

## 02 — Success Morph / 成功状态

关键词：

```text
SUCCESS
CHECK
MORPH
CONFIRM
```

中文关键词：

```text
成功反馈
勾选
状态完成
确认
```

### 动效逻辑

承接 Loading 状态。

Spinner 停止。

旋转圆环逐渐变为 Checkmark。

按钮颜色由 Primary Color 变成 Success Green。

### 关键帧

```text
LOADING
→ SPINNER STOP
→ CHECK DRAW
→ SUCCESS
```

最后按钮可显示：

```text
✓ DONE
```

---

## 03 — Progress Button / 进度按钮

关键词：

```text
PROGRESS
UPLOAD
TRACK
COMPLETE
```

中文关键词：

```text
进度
上传
过程反馈
完成
```

### 动效逻辑

点击：

```text
UPLOAD
```

后，按钮底部或背景成为 Progress Bar。

例如：

```text
0% → 32% → 68% → 100%
```

最终转换为成功状态。

### 关键帧

```text
UPLOAD
→ 30%
→ 70%
→ 100%
→ COMPLETE
```

适合表现文件上传、生成任务、导出等操作。

---

## 04 — Icon Morph / 图标变形

关键词：

```text
ICON
MORPH
SVG
TRANSITION
```

中文关键词：

```text
图标变形
路径过渡
状态转换
连续动画
```

### 动效逻辑

按钮中的图标在不同状态之间连续 Morph。

例如：

```text
＋ → ×
```

或者：

```text
♡ → ♥
```

或者：

```text
↓ → ✓
```

### 关键帧

必须展示中间 Path Shape。

不是直接替换两个图标。

要能看到真正的 SVG Morphing 感。

---

## 05 — Text Swap / 文案切换

关键词：

```text
TEXT
SWAP
MASK
SLIDE
```

中文关键词：

```text
文字替换
遮罩
上下滑动
状态提示
```

### 动效逻辑

默认：

```text
FOLLOW
```

Hover：

文字向上滑出。

新的：

```text
LET'S GO →
```

从下方滑入。

按钮自身不需要明显变化。

### 关键帧

```text
FOLLOW
→ OLD TEXT UP
→ CROSSING
→ NEW TEXT
```

重点展示文字 Mask 动画。

---

# 第 04 张图片

## 标题

```text
前端按钮动效风格参考 04
BUTTON MOTION DESIGN REFERENCE
```

---

## 01 — Elastic Stretch / 弹性拉伸

关键词：

```text
ELASTIC
STRETCH
SPRING
PLAYFUL
```

中文关键词：

```text
弹性
拉伸
回弹
柔性形变
```

### 动效逻辑

Hover 或 Cursor 快速靠近按钮时：

按钮沿运动方向产生 Stretch。

例如：

宽度：

```text
100% → 112% → 96% → 102% → 100%
```

高度产生轻微反向压缩。

形成 Squash & Stretch 动画原则。

### 静态展示

使用 4–5 个明显不同的形变量。

突出弹性回弹。

---

## 02 — Blob Morph / 有机形变

关键词：

```text
BLOB
ORGANIC
MORPH
FLUID
```

中文关键词：

```text
有机形变
流体边缘
柔软
非规则变化
```

### 动效逻辑

默认按钮是圆角矩形。

Hover：

边缘开始产生柔和、不规则形变。

按钮轮廓从标准圆角矩形逐渐变成 Organic Blob。

### 关键帧

```text
RECT
→ SOFT DISTORTION
→ BLOB
→ RETURN
```

可以使用渐变背景。

适合创意、艺术、音乐类网站。

---

## 03 — Particle Burst / 粒子爆发

关键词：

```text
PARTICLE
BURST
CELEBRATE
FEEDBACK
```

中文关键词：

```text
粒子
爆发
完成反馈
庆祝
```

### 动效逻辑

用户完成重要动作后：

按钮中心产生短暂粒子爆发。

例如：

点击：

```text
LIKE
```

后变成：

```text
♥ LIKED
```

同时周围出现少量：

- 星点
- 圆点
- 小线条
- Confetti

### 关键帧

```text
CLICK
→ BURST
→ MAX PARTICLES
→ FADE
```

效果应克制，不要变成烟花。

---

## 04 — 3D Flip / 3D 翻转

关键词：

```text
3D
FLIP
DEPTH
ROTATE
```

中文关键词：

```text
翻转
空间
立体
状态切换
```

### 动效逻辑

按钮具有正反两个表面。

默认正面：

```text
DOWNLOAD
```

Click 后沿 X 或 Y 轴翻转。

背面显示：

```text
DOWNLOADED ✓
```

### 关键帧

```text
0°
→ 45°
→ 90°
→ 135°
→ 180°
```

使用透视效果明确展示 3D Rotation。

---

## 05 — Cursor Interaction / 光标互动

关键词：

```text
CURSOR
INTERACTIVE
FOLLOW
MICRO MOTION
```

中文关键词：

```text
光标互动
局部跟随
微动效
动态反馈
```

### 动效逻辑

Cursor 进入按钮后：

按钮内部会生成一个跟随 Cursor 的高亮区域。

可以表现为：

- 小光斑
- Radial Gradient
- Spotlight
- Gradient Blob

Cursor 移动时光斑同步跟随。

### 静态图表达

同时展示 3 个 Cursor 位置：

```text
LEFT
CENTER
RIGHT
```

每个位置对应不同的按钮内部 Spotlight 位置。

通过虚线轨迹连接 Cursor。

---

# 四张图片统一质量控制

四张图片必须像同一本专业的：

**Button Motion Design Reference Book**

连续的第 01–04 页。

统一：

- 纸张背景
- 页面比例
- 主标题尺寸
- 英文副标题
- 顶部区域高度
- 左侧信息栏宽度
- 案例区域高度
- 编号位置
- 字体体系
- 留白
- 分隔线
- 圆角
- 边距
- Motion Spec 标注方式

每张图严格包含 5 个案例。

---

# 动效表现重点

右侧展示的重点不是「按钮长什么样」。

而是：

**按钮从状态 A 如何运动到状态 B。**

每种风格都应该至少包含：

```text
STATE A
→ TRANSITION
→ STATE B
```

复杂交互可以包含：

```text
STATE A
→ INTERMEDIATE 01
→ INTERMEDIATE 02
→ STATE B
```

必须让观看者只看静态图，就能够理解：

- 哪个元素发生移动
- 从哪里移动到哪里
- 哪个属性发生变化
- 动画方向是什么
- 动画结束状态是什么

可灵活加入：

```text
Cursor
Motion Trail
Direction Arrow
Ghost Frame
Opacity Trail
Path
Keyframe
Timing
Easing
Scale Value
Transform Value
```

---

# 避免错误

不要把它做成普通 Button UI Kit。

不要只展示不同颜色和形状的按钮。

不要每个案例只有一个按钮。

不要只改变：

- 圆角
- 配色
- 边框
- 字体

这些属于静态 Style，不足以代表 Motion Design。

必须展示：

**交互前后状态 + 中间动画过程。**

不要让所有按钮都使用：

- 蓝紫渐变
- Glassmorphism
- 大圆角
- Glow
- 科技风

20 种按钮之间必须具有明显的动画机制差异。

统一的是：

**图鉴页面设计系统。**

不统一的是：

**每种按钮自身的 Motion Language。**

---

# 最终输出规则

最终必须输出：

```text
Image 1 = 前端按钮动效风格参考 01
Image 2 = 前端按钮动效风格参考 02
Image 3 = 前端按钮动效风格参考 03
Image 4 = 前端按钮动效风格参考 04
```

共 **4 张独立图片文件**。

每张图片：

- 3:4 竖版
- 5 种按钮动效
- 一个完整页面
- 独立构图

再次强调：

**禁止生成一张包含 4 页的拼图。**

**禁止四宫格。**

**禁止 2×2 Contact Sheet。**

**禁止将 01、02、03、04 放进同一个画布。**

**必须分别生成 4 次，每次只生成其中一张图片。**

如果图像生成系统支持单独调用，则按以下方式执行：

```text
第一次生成：只生成「前端按钮动效风格参考 01」
第二次生成：只生成「前端按钮动效风格参考 02」
第三次生成：只生成「前端按钮动效风格参考 03」
第四次生成：只生成「前端按钮动效风格参考 04」
```

每次：

```text
n = 1
```

不要一次生成包含四张页面的综合图片。

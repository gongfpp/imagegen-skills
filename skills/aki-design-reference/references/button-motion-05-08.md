# 前端按钮动效风格参考图鉴 05–08 生成 Prompt

继续生成「前端按钮动效设计风格参考图鉴」系列。

这是前面：

- 前端按钮动效风格参考 01
- 前端按钮动效风格参考 02
- 前端按钮动效风格参考 03
- 前端按钮动效风格参考 04

的连续系列。

本次继续生成：

- 第 5 张：前端按钮动效风格参考 05
- 第 6 张：前端按钮动效风格参考 06
- 第 7 张：前端按钮动效风格参考 07
- 第 8 张：前端按钮动效风格参考 08

共 **4 张彼此独立的图片文件**。

每张图片包含 **5 种不同的按钮交互与动效设计风格**。

本批共新增 **20 种按钮动效**。

---

# 重要输出要求

必须输出 **4 张独立图片**。

每张图片都是完整的：

**3:4 竖版设计图。**

禁止：

- 四宫格
- 2×2 拼图
- Contact Sheet
- 总览图
- 一张超长图
- 在同一个画布里同时放 05、06、07、08
- 生成后让我手动裁切

必须分别生成：

```text
Image 1 = 前端按钮动效风格参考 05
Image 2 = 前端按钮动效风格参考 06
Image 3 = 前端按钮动效风格参考 07
Image 4 = 前端按钮动效风格参考 08
```

如果生成系统支持多次调用：

```text
第一次：只生成 05
第二次：只生成 06
第三次：只生成 07
第四次：只生成 08
```

每次只生成：

```text
n = 1
```

---

# 系列整体视觉

必须完全延续前 01–04 的图鉴设计系统。

整体类似：

- UI/UX Design Reference Book
- Motion Design Handbook
- Interaction Design Reference
- Front-end Motion Design Guide
- Figma / Framer / Rive 动效案例图鉴
- 高质量设计杂志

背景：

**非常浅的暖灰白。**

页面干净、高级、克制。

顶部为统一标题。

标题格式：

```text
前端按钮动效风格参考 05
BUTTON MOTION DESIGN REFERENCE
```

依次替换为 06、07、08。

右上角保留极小辅助文字：

```text
探索交互细节
创造更自然的反馈体验

MOTION
INTERACTION
FEEDBACK
```

---

# 页面固定布局

每张图从上至下包含 **5 个横向案例区域**。

每个案例：

左侧约 25%–28%。

右侧约 72%–75%。

## 左侧信息区

包含：

```text
编号

英文名称
中文名称

KEYWORD
KEYWORD
KEYWORD
KEYWORD

中文关键词
中文关键词
中文关键词
```

## 右侧动效展示区

展示同一个按钮的 **3–5 个连续关键帧**。

例如：

```text
DEFAULT
→ HOVER
→ INTERMEDIATE
→ ACTIVE
```

或者：

```text
PRESS
→ PROCESS
→ FEEDBACK
→ COMPLETE
```

必须通过静态关键帧让人理解运动过程。

可以使用：

- Cursor
- Motion Path
- Arrow
- Ghost Frame
- Motion Blur
- Position Trail
- Scale
- Rotation
- Mask
- Clip Path
- Stroke
- Progress
- Blur
- Opacity
- Spring
- Easing Curve

辅助表达。

右下角可以加入很小的 Motion Spec：

```text
Duration   180ms
Delay       20ms
Ease       ease-out
Property   transform
```

或者：

```text
X
0 → 12 → -3 → 0
```

---

# 前端按钮动效风格参考 05

## 01 — Shine Sweep / 高光扫过

关键词：

```text
SHINE
LIGHT
SWEEP
REFLECTION
```

中文关键词：

```text
高光
扫光
反射
质感
```

### 动效逻辑

默认按钮为深色实体按钮。

Hover 后：

一道窄而明亮的高光从按钮左上方进入。

以斜向角度快速扫过按钮表面。

随后从右下方离开。

类似玻璃、金属或高级产品表面的反射高光。

### 关键帧

```text
IDLE
→ LIGHT ENTER
→ CENTER SHINE
→ LIGHT EXIT
```

高光区域必须清楚展示位置变化。

不能把它画成静态渐变。

适合：

- Premium CTA
- SaaS
- AI 产品
- 高端品牌
- 会员按钮

---

## 02 — Border Beam / 流光边框

关键词：

```text
BEAM
BORDER
TRAVEL
ENERGY
```

中文关键词：

```text
流光
边框
环绕
能量
```

### 动效逻辑

按钮主体保持稳定。

一小段高亮光束沿按钮边框持续移动。

光束按照：

```text
TOP
→ RIGHT
→ BOTTOM
→ LEFT
```

绕按钮一圈。

可通过渐变 Stroke 表现。

### 关键帧

```text
12 O'CLOCK
→ 3 O'CLOCK
→ 6 O'CLOCK
→ 9 O'CLOCK
```

画面中需要明确展示同一段光束沿边缘运动。

适合：

- AI Generate
- Premium
- Start
- Upgrade
- 游戏按钮

---

## 03 — Radial Reveal / 径向揭示

关键词：

```text
RADIAL
MASK
REVEAL
CURSOR
```

中文关键词：

```text
径向
遮罩
扩张
揭示
```

### 动效逻辑

Hover 或 Click 点成为圆心。

新的按钮颜色从 Cursor 所在位置以圆形向外扩张。

最终覆盖整个按钮。

### 关键帧

```text
DEFAULT
→ SMALL CIRCLE
→ LARGE CIRCLE
→ FULL COVER
```

必须体现：

**扩张圆心来自鼠标位置。**

与 Ripple 不同：

Ripple 是波纹消失。

Radial Reveal 是新背景真正取代原背景。

---

## 04 — Underline Grow / 下划线生长

关键词：

```text
LINE
GROW
MINIMAL
DIRECTION
```

中文关键词：

```text
线条
生长
极简
方向
```

### 动效逻辑

这是一个极简文字型按钮。

默认只有文字：

```text
VIEW PROJECT
```

Hover 时：

底部细线从左侧开始生长。

长度：

```text
0%
→ 35%
→ 70%
→ 100%
```

同时文字可以产生极轻微位移。

### 关键帧

明确显示线条逐渐延伸。

适合：

- Portfolio
- Editorial
- Luxury
- Architecture
- Minimal Website

---

## 05 — Icon Orbit / 图标环绕

关键词：

```text
ICON
ORBIT
ROTATE
PLAYFUL
```

中文关键词：

```text
图标
环绕
旋转
趣味
```

### 动效逻辑

按钮中存在一个箭头或小图标。

Hover 后：

图标从按钮右侧离开原位置。

沿圆形或半圆形轨迹绕文字运动。

随后回到新的位置。

例如：

```text
NEXT →
```

箭头绕按钮半圈后重新进入右侧。

### 静态表达

必须画出：

- 起始 Icon
- Motion Path
- 中间 Icon
- 最终 Icon

形成清晰的 Orbit Path。

---

# 前端按钮动效风格参考 06

## 01 — Hold to Confirm / 长按确认

关键词：

```text
HOLD
CONFIRM
PROGRESS
SAFETY
```

中文关键词：

```text
长按
确认
进度
防误触
```

### 动效逻辑

默认：

```text
HOLD TO DELETE
```

用户持续按住按钮。

按钮内部的填充进度从左向右增长。

```text
0%
→ 30%
→ 70%
→ 100%
```

完成后变为：

```text
DELETED ✓
```

### 静态展示

显示 Finger / Cursor 持续按压。

按钮内部有清晰的 Hold Progress。

适合：

- Delete
- Reset
- Publish
- Confirm Purchase
- 危险操作

---

## 02 — Drag to Confirm / 拖动确认

关键词：

```text
DRAG
SLIDE
CONFIRM
GESTURE
```

中文关键词：

```text
拖动
滑动
确认
手势
```

### 动效逻辑

按钮类似 Slider。

左侧有圆形 Handle。

默认：

```text
→ SLIDE TO CONFIRM
```

用户拖动 Handle：

```text
0%
→ 35%
→ 75%
→ 100%
```

到最右端后：

按钮整体转换为成功状态。

```text
✓ CONFIRMED
```

### 静态展示

明确画出：

- Cursor
- Drag Path
- Handle 的多个位置
- Progress
- Final State

---

## 03 — Shake Error / 错误震动

关键词：

```text
ERROR
SHAKE
WARNING
FEEDBACK
```

中文关键词：

```text
错误
震动
警告
失败反馈
```

### 动效逻辑

用户点击后验证失败。

按钮快速左右震动。

位移可以为：

```text
0
→ -8
→ +7
→ -5
→ +3
→ 0
```

同时颜色从 Primary 变为 Error Red。

### 静态展示

通过多个半透明残影展示横向 Shake。

最终显示：

```text
TRY AGAIN
```

或：

```text
ERROR !
```

适合表单错误反馈。

---

## 04 — Bounce Confirm / 弹跳确认

关键词：

```text
BOUNCE
SUCCESS
SPRING
ENERGY
```

中文关键词：

```text
弹跳
确认
回弹
活力
```

### 动效逻辑

Click 后：

按钮先缩小。

随后向上轻跳。

落下时产生轻微压缩。

最后恢复正常尺寸。

### 运动过程

```text
REST
→ SQUASH
→ JUMP
→ LAND
→ REST
```

必须明显体现经典动画原则：

**Squash & Stretch。**

适合：

- 游戏
- 教育
- 社交
- 娱乐产品

---

## 05 — Lock Unlock / 锁定解锁

关键词：

```text
LOCK
UNLOCK
STATE
ICON
```

中文关键词：

```text
锁定
解锁
状态转换
图标反馈
```

### 动效逻辑

按钮默认：

```text
🔒 LOCKED
```

点击后：

锁扣向上弹起。

Lock Icon 发生机械式旋转。

文字变为：

```text
🔓 UNLOCKED
```

### 关键帧

```text
LOCKED
→ SHACKLE MOVE
→ ROTATE
→ UNLOCKED
```

重点展示 Icon 自身的微交互动效。

---

# 前端按钮动效风格参考 07

## 01 — Text Scramble / 字符扰动

关键词：

```text
TEXT
SCRAMBLE
DECODE
DIGITAL
```

中文关键词：

```text
字符
扰动
解码
数字感
```

### 动效逻辑

Hover 时：

原始文字：

```text
EXPLORE
```

快速变成随机字符：

```text
E#P@0?E
```

随后逐字符恢复成：

```text
EXPLORE →
```

### 关键帧

```text
EXPLORE
→ E#7@?X
→ EXPL?RE
→ EXPLORE →
```

适合：

- Tech
- Developer
- Cyberpunk
- AI
- Experimental UI

---

## 02 — Rolling Text / 滚轮文字

关键词：

```text
ROLL
TEXT
VERTICAL
LOOP
```

中文关键词：

```text
文字滚动
纵向切换
循环
轮转
```

### 动效逻辑

按钮内部文字像老虎机滚轮。

旧文字向上滚动离开。

新文字从下方进入。

例如：

```text
VIEW
↓
OPEN
↓
EXPLORE
```

### 关键帧

需要通过 Mask Window 表现文字只在按钮内部可见。

与普通 Text Swap 相比：

强调连续滚轮感和重复循环感。

---

## 03 — Letter Spread / 字距展开

关键词：

```text
TYPE
SPACING
EXPAND
ELEGANT
```

中文关键词：

```text
字距
展开
排版
优雅
```

### 动效逻辑

默认：

```text
EXPLORE
```

Hover：

按钮宽度略微增加。

文字 Letter Spacing 同时增大。

```text
EXPLORE
→ E X P L O R E
```

Mouse Leave 后缓慢恢复。

### 视觉效果

非常克制。

高级品牌感。

适合：

- Luxury
- Fashion
- Architecture
- Portfolio
- Editorial

---

## 04 — Arrow Loop / 箭头循环

关键词：

```text
ARROW
LOOP
MASK
DIRECTION
```

中文关键词：

```text
箭头
循环
方向
遮罩
```

### 动效逻辑

Hover 后：

右侧箭头向右离开按钮。

同时另一枚相同箭头从左侧或右侧重新进入。

形成：

```text
→ EXIT
→ HIDDEN
→ NEW →
```

无限循环视觉。

### 关键帧

必须明显展示旧箭头和新箭头是两个连续状态。

适合：

```text
NEXT
EXPLORE
CONTINUE
VIEW MORE
```

---

## 05 — Character Wave / 字符波浪

关键词：

```text
TYPE
WAVE
STAGGER
MOTION
```

中文关键词：

```text
字符
波浪
错峰
节奏
```

### 动效逻辑

Hover 后：

按钮中文字每个字符依次向上移动。

形成 Wave。

例如：

```text
E X P L O R E
```

字符依次：

```text
0px
-5px
-9px
-5px
0px
```

然后恢复。

### 静态表现

画出文字不同字符位于不同 Y 轴高度。

增加很小的 Stagger 时间：

```text
20ms
40ms
60ms
80ms
```

体现逐字符动画。

---

# 前端按钮动效风格参考 08

## 01 — Expand to Panel / 按钮展开面板

关键词：

```text
EXPAND
PANEL
MORPH
CONTEXT
```

中文关键词：

```text
展开
面板
形变
上下文
```

### 动效逻辑

默认是一个普通：

```text
SHARE
```

按钮。

点击后：

按钮横向或纵向展开。

内部出现：

```text
X
LINK
MAIL
COPY
```

等多个操作。

### 关键帧

```text
BUTTON
→ EXPANDING
→ WIDE PANEL
→ ACTIONS
```

强调按钮本身直接 Morph 成功能面板。

---

## 02 — Button to Input / 按钮变输入框

关键词：

```text
MORPH
INPUT
FORM
TRANSITION
```

中文关键词：

```text
输入框
形变
表单
连续转换
```

### 动效逻辑

默认：

```text
SUBSCRIBE
```

点击后：

按钮逐渐变宽。

文字离开。

内部出现 Input Cursor。

最终变成：

```text
YOUR EMAIL...      →
```

### 关键帧

```text
BUTTON
→ WIDTH EXPAND
→ TEXT FADE
→ INPUT FIELD
```

适合 Newsletter 或搜索交互。

---

## 03 — Directional Hover / 方位感应

关键词：

```text
DIRECTION
CURSOR
ENTRY
ADAPTIVE
```

中文关键词：

```text
方位
鼠标进入
自适应
方向反馈
```

### 动效逻辑

按钮根据 Cursor 从哪个方向进入，决定背景动画方向。

例如：

Cursor 从左侧进入：

```text
LEFT → RIGHT
```

从顶部进入：

```text
TOP → BOTTOM
```

### 静态图展示

同时展示四种方向：

```text
LEFT ENTRY
RIGHT ENTRY
TOP ENTRY
BOTTOM ENTRY
```

但保持为同一个案例区域。

使用箭头表示 Cursor Entry Direction。

这是一个典型高级前端 Hover Interaction。

---

## 04 — Gooey Merge / 黏性融合

关键词：

```text
GOOEY
MERGE
SOFT
FLUID
```

中文关键词：

```text
黏性
融合
流体
柔软
```

### 动效逻辑

按钮旁存在小圆形元素或 Icon。

Hover 时：

小圆向按钮靠近。

两个形状之间出现液态连接。

最终完全融合进按钮。

Mouse Leave 后重新分离。

### 关键帧

```text
SEPARATE
→ APPROACH
→ GOOEY BRIDGE
→ MERGED
```

重点体现 Metaball / Gooey Filter 的视觉特征。

---

## 05 — Explode & Rebuild / 解构重组

关键词：

```text
EXPLODE
REBUILD
PARTS
EXPERIMENTAL
```

中文关键词：

```text
解构
重组
碎片
实验
```

### 动效逻辑

Hover 或 Click 后：

按钮边框、文字、箭头等不同元素短暂向外分离。

形成若干视觉碎片。

随后快速重新组合。

### 关键帧

```text
NORMAL
→ SEPARATE
→ MAX EXPLOSION
→ REASSEMBLE
→ NORMAL
```

元素可以包括：

- Background
- Stroke
- Text
- Arrow
- Corner
- Accent Shape

但不能真的破碎成几十个粒子。

应该保持高级的平面 Motion Graphic 风格。

适合：

- Creative Agency
- Experimental Portfolio
- Music
- Fashion
- Art Website

---

# 统一 Motion Spec

每个案例右侧可加入少量技术标注。

例如：

```text
Trigger    Hover
Duration   240ms
Ease       cubic-bezier(.22,.8,.2,1)
```

或者：

```text
Transform
X   0 → 12px
Y   0 → -4px
```

复杂 Spring 动画：

```text
Spring
Stiffness   300
Damping      22
```

参数只作为视觉辅助。

不要占据主要画面。

---

# 本批 20 种动效总览

05：

```text
01 Shine Sweep
02 Border Beam
03 Radial Reveal
04 Underline Grow
05 Icon Orbit
```

06：

```text
01 Hold to Confirm
02 Drag to Confirm
03 Shake Error
04 Bounce Confirm
05 Lock Unlock
```

07：

```text
01 Text Scramble
02 Rolling Text
03 Letter Spread
04 Arrow Loop
05 Character Wave
```

08：

```text
01 Expand to Panel
02 Button to Input
03 Directional Hover
04 Gooey Merge
05 Explode & Rebuild
```

---

# 与前 01–04 的关系

本批禁止重复前一批已经重点展示过的机制：

```text
Fill Sweep
Border Draw
Magnetic Hover
Press Scale
Arrow Slide

Ripple Click
Glow Pulse
Liquid Fill
Split Reveal
Shadow Lift

Loading Morph
Success Morph
Progress Button
Icon Morph
Text Swap

Elastic Stretch
Blob Morph
Particle Burst
3D Flip
Cursor Interaction
```

05–08 应明显表现新的 Motion Mechanism。

不要只是把旧动效换颜色或换名称。

---

# 统一质量控制

4 张图片必须像同一本：

**BUTTON MOTION DESIGN REFERENCE**

中的连续第 05–08 页。

必须保持完全一致：

- 3:4 比例
- 暖灰白背景
- 主标题位置
- 英文副标题
- 左侧编号
- 左侧文字区域
- 右侧演示区域
- 每页 5 个案例
- 案例高度
- 分隔方式
- 字体系统
- 留白
- Motion Spec 位置
- 关键帧表达方式

统一的是：

**图鉴本身的 Editorial Design System。**

每个案例不同的是：

**Button Motion Language。**

---

# 最重要的视觉要求

不要做成普通静态按钮 UI Kit。

不要只展示：

```text
Default
Hover
Pressed
Disabled
```

四个几乎相同的按钮。

必须让画面能够解释：

```text
它从哪里开始
↓
什么元素开始运动
↓
怎么运动
↓
中间发生什么
↓
最终变成什么
```

每种案例至少具有 3 个视觉差异明显的关键帧。

复杂案例建议 4–5 帧。

可以加入：

- Cursor
- Hand Pointer
- Motion Arrow
- Ghost Frame
- Path
- Position Marker
- Mask
- Progress
- Timeline
- Easing
- Timing

帮助说明动效。

---

# 最终输出

必须生成 **4 个独立图片文件**：

```text
前端按钮动效风格参考 05
前端按钮动效风格参考 06
前端按钮动效风格参考 07
前端按钮动效风格参考 08
```

每张：

```text
3:4
5 个案例
一个完整页面
```

再次强调：

**禁止把 4 张图合成一张。**

**禁止四宫格。**

**禁止 2×2 拼图。**

**禁止 Contact Sheet。**

**禁止输出需要后期裁切的大图。**

必须单独调用图片生成流程 4 次。

每次只生成其中一页。

每次：

```text
n = 1
```

---
name: aki-design-reference
description: 生成前端、App 与游戏 UI 的设计参考图鉴，支持美术风格比较、功能结构分类、网页、按钮动效和页面转场；也可只输出生图 prompt。
---

# 设计参考图鉴

根据用户当次主题选择一份参考，只加载需要的内容。本入口为本次发布时从原对话 prompt 封装；references 中保留原文。

## 选择模板

- 同一主体比较不同美术风格：读取 [design-style-10-pages.md](references/design-style-10-pages.md)。
- 比较功能、结构、交互模式：读取 [design-pattern-10-pages.md](references/design-pattern-10-pages.md)。
- 只沿用图鉴布局、由执行 Agent 选择内容：读取 [layout-master-4-pages.md](references/layout-master-4-pages.md)。
- 网页风格 01–04 / 05–08：读取 [web-style-01-04.md](references/web-style-01-04.md) 或 [web-style-05-08.md](references/web-style-05-08.md)。
- 按钮动效 01–04 / 05–08：读取 [button-motion-01-04.md](references/button-motion-01-04.md) 或 [button-motion-05-08.md](references/button-motion-05-08.md)。
- 页面转场：读取 [page-transition-motion-01-04.md](references/page-transition-motion-01-04.md)。
- 落地页：读取 [landing-page-01-04.md](references/landing-page-01-04.md)。
- 导航栏：读取 [navbar-01-04.md](references/navbar-01-04.md)。
- 旧版四页美术风格模板仅在需要还原旧系列时读取 [archive/design-style-4-pages.md](references/archive/design-style-4-pages.md)。

## 执行

用户明确的主题、数量、页码和输出形式优先。未指定时，采用所选模板默认值。若只要 prompt，输出文字；若要图片，使用当前环境实际支持的图片生成工具。

开始前规划完整案例清单，区分页面序号与页内案例编号。系列页码连续；每次生成一张独立图鉴页面，每页内部可以有多个案例。不要把多张完整页面合成一个画布。

图鉴母版统一，案例内容真实区分。风格模式应改变字体、形状、材质和构图；分类模式应体现功能或交互差异。局部组件要放大，静态动效参考采用关键帧与必要标注。

生成后检查独立文件数量、页码、案例数量、文字与差异。图片中的动效示意不等于可运行动画；没有实际图片工具时说明限制并交付可执行 prompt，不声称已生成图片。


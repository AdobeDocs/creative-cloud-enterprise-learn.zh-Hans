---
title: 模板库
description: 浏览现成的Firefly图模板，您可以打开这些模板并根据自己的项目进行调整
feature: Image Editing, Gen AI
role: User
level: Beginner
jira: KT-
hide: true
hidefromtoc: true
source-git-commit: af06d76d4cad7ccf7adeb845d71525480b68ea4f
workflow-type: tm+mt
source-wordcount: '878'
ht-degree: 0%

---

# &#x200B;5. 模板库

Firefly图形模板的快速引用索引，按每个模板的生产或操作进行组织。 每个示例都是一个起点 — 在生产中使用模板之前，替换您自己的品牌、产品和提示。

## 图像生成和样式

* [**入门 — 生成映像**](/help/firefly/graph/templates/get-started-gen-image.md) — 此模板是一个基本图形：一个提示节点进入一个生成节点到一个输出中。 将其用作与任何全新的用户一起打开的第一个模板。
* [**一致的角色生成**](/help/firefly/graph/templates/character-gen.md) — 在此图表模板中，您将加载一个角色的参考图像，然后为每个新拍摄互换场景或姿势提示。 当周围的场景发生变化时，角色引用会保持锁定状态。
* [**样式提取**](/help/firefly/graph/templates/style-extraction.md) — 在此图表模板中，您输入参考图像以提取其颜色、亮度和纹理处理。 然后，您可以将该处理方法应用于通过同一图形运行的任何新图像。
* [**日落氛围**](/help/firefly/graph/templates/sunset-vibes.md) — 在此图表模板中，您可以从文本提示创建3D排版图像。 模板会自动处理放置和色彩平衡。

## 分段与合成

* [**入门 — 分割图像**](/help/firefly/graph/templates/get-started-segment-image.md) — 在此图形模板中，您将加载任何源图像并运行分割节点以将主体与其背景隔离。 与背景替换节点搭配，生成干净的抠图。
* [**合成和混合图层**](/help/firefly/graph/templates/composite-blend-layers.md) — 在此图表模板中，您将产品抠图和背景场景栈叠为单独的图层输入。 调整混合模式和光照节点，直到合成图像读取为一张。
* [**可选颜色校正**](/help/firefly/graph/templates/selective-color-correction.md) — 在此图表模板中，您将遮盖需要校正的特定区域并仅在该节点上设置目标颜色。 图像的其余部分将原封不动地通过图形。

## 视频和运动

* [**入门 — 视频生成**](/help/firefly/graph/templates/get-started-video-gen.md) — 在此图表模板中，您为已批准的静态关键图稿和短动态提示馈送内容。 模板会生成一个基于相同关键图稿（而不是新的镜头）构建的视频剪辑。
* [**Bullet Time VFX**](/help/firefly/graph/templates/bullet-time-vfx.md) — 在此图表模板中，您为主页产品或主题图像馈送源以围绕它生成旋转的一系列角度，然后自动拼接冻结帧扫描。

## 故事板

* [**文本到情节提要**](/help/firefly/graph/templates/text-to-storyboard.md) — 在此图表模板中，您将使用文章中的元素替换文本输入节点。 每行都将成为其自己的故事板框架，并作为单个面板集按顺序生成和排列以供审阅。
* [**故事板生成器**](/help/firefly/graph/templates/storyboard-builder.md) — 在此图表模板中，您可以按场景构建故事板场景，每个故事节拍添加一个节点。 在锁定最终面板顺序之前，请重新排序节点以测试不同的序列。

## 3D和字符

* [**实时着色器**](/help/firefly/graph/templates/real-time-shaders.md) — 在此图表模板中，您从一个图像开始并应用三个不同的自定义着色器并实时预览结果。 直接在节点上调整着色器参数，而不是从头开始重新渲染。
* [**字符模型生成**](/help/firefly/graph/templates/character-model-generation.md) — 在此图表模板中，您将创建插图的3D动画样式。 模板将生成一个基础3D模型传递，此模型传递已准备好交给建模器清理，而不是从空白场景开始。
* [**乙烯基玩具设计**](/help/firefly/graph/templates/vinyl-toy-design.md) — 在此图表模板中，您输入角色或吉祥物参考，并将其渲染为风格化的乙烯基玩具形式。 许可或产品审查幻灯片组有多种变通方法。
* [**素描到3D转折**](/help/firefly/graph/templates/sketch-to-3d.md) — 在此图表模板中，您可以将素描转换为3D角色。 该图形从中构建旋转的3D转折，可在任何物理原型之前进行内部设计审阅。

## 产品和品牌模型

* [**品牌形象可视化**](/help/firefly/graph/templates/branding-visualization.md) — 在此图表模板中，了解如何在产品场景中可视化徽标或品牌。 输入品牌准则或徽标和调色板，图形一次性输出静态关键图稿和短动态通道，因此两种格式在视觉上保持一致。
* [**品牌产品模型**](/help/firefly/graph/templates/brand-product-mockup.md) — 在此图表模板中，了解如何在不同的场景中可视化您的产品。 您将产品渲染或照片放入模型节点，然后图形会将其置于完全品牌化的场景中，并且光照和阴影会自动与该场景匹配。
* [**编辑摄影**](/help/firefly/graph/templates/editorial-photoshoot.md) — 在此图表模板中，您将加载模型参考并交换服装输入以生成每个新外观。 姿势和光照节点在整个场景中保持锁定状态，以获得一致的编辑感觉。
* [**摄影工作室**](/help/firefly/graph/templates/photography-studio.md) — 在此图表模板中，您可以在工作室背景上放置产品渲染，并调整光照，直到结果看起来像真实的工作室拍摄。
* [**将贴花应用于表面**](/help/firefly/graph/templates/decal-to-surfaces.md) — 在此图表模板中，您将基础产品模型和贴花或徽标资源作为单独的输入加载。 模板将贴花包络到曲面几何上，使其正确跟随轮廓。

## 批处理与一致性操作

* [**设计系统生成器**](/help/firefly/graph/templates/design-system-generator.md) — 在此图表模板中，您将基于网站屏幕截图生成设计系统。 图形在单个批处理运行中生成一组匹配的图标、图案和布局组件。
* [**大头照生成**](/help/firefly/graph/templates/headshots-generation.md) — 在此图表模板中，您将协调一批公司大头照。 加载源照片，每人一个，图形一圈就规范化光照、背景和裁剪整个集。

返回[开始使用Firefly图形](https://experienceleague.adobe.com/zh-hans/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/overview-firefly-graph)。
---
title: 模板库
description: 浏览现成的Firefly图模板，您可以打开这些模板并根据自己的项目进行调整
feature: Image Editing, Gen AI
role: User
level: Beginner
jira: KT-
hide: true
hidefromtoc: true
source-git-commit: aa0ae4747f081c69d8a01d3f9acdd7844cca6afe
workflow-type: tm+mt
source-wordcount: '996'
ht-degree: 2%

---

# &#x200B;5. 模板库

Firefly图形模板的快速引用索引，按每个模板的生产或操作进行组织。 每个示例都是一个起点 — 在生产中使用模板之前，替换您自己的品牌、产品和提示。

## 图像生成和样式

| 图形模板 | 描述 | [!BADGE 用例]{type=Informative tooltip="使用案例"} |
|---|---|---|
| [**入门 — 生成图像**](/help/firefly/graph/templates/get-started-gen-image.md) | 该模板是一个基本图形：一个提示节点到一个生成节点到一个输出。 将其用作与任何全新的用户一起打开的第一个模板。 | 零售、卫生、教育 |
| [**一致的字符生成**](/help/firefly/graph/templates/character-gen.md) | 在此图表模板中，您需要加载角色的一个参考图像，然后交换每个新拍摄的场景或姿势提示。 当周围的场景发生变化时，角色引用会保持锁定状态。 | 旅行、零售、教育 |
| [**样式提取**](/help/firefly/graph/templates/style-extraction.md) | 在此图表模板中，您输入参考图像以对其进行颜色、光和纹理处理。 然后，您可以将该处理方法应用于通过同一图形运行的任何新图像。 | 旅行、零售、饮料 |
| [**日落氛围**](/help/firefly/graph/templates/sunset-vibes.md) | 在此图表模板中，您可以从文本提示创建3D排版图像。 模板会自动处理放置和色彩平衡。 | 旅行、饮料、零售 |

## 分段与合成

| 图形模板 | 描述 | [!BADGE 用例]{type=Informative tooltip="使用案例"} |
|---|---|---|
| [**入门 — 分段图像**](/help/firefly/graph/templates/get-started-segment-image.md) | 在此图表模板中，您需要加载任何源图像并运行分割节点以将主体与其背景隔离。 与背景替换节点搭配，生成干净的抠图。 | 健康、零售、汽车 |
| [**合成和混合图层**](/help/firefly/graph/templates/composite-blend-layers.md) | 在此图表模板中，您将产品抠图和背景场景栈叠为单独的图层输入。 调整混合模式和光照节点，直到合成图像读取为一张。 | 饮料、零售、旅行 |
| [**可选颜色校正**](/help/firefly/graph/templates/selective-color-correction.md) | 在此图形模板中，您将遮盖需要校正的特定区域并仅在该节点上设置目标颜色。 图像的其余部分将原封不动地通过图形。 | 通信与电信、零售、金融 |

## 视频和运动

| 图形模板 | 描述 | [!BADGE 用例]{type=Informative tooltip="使用案例"} |
|---|---|---|
| [**入门 — 视频生成**](/help/firefly/graph/templates/get-started-video-gen.md) | 在此图表模板中，您输入批准的静态关键图稿和短动态提示。 模板会生成一个基于相同关键图稿（而不是新的镜头）构建的视频剪辑。 | 金融、饮料、零售 |
| [**Bullet Time VFX**](/help/firefly/graph/templates/bullet-time-vfx.md) | 在此图表模板中，您将馈送主产品或主体图像以在其周围生成一系列旋转角度，然后自动缝合冻结帧扫描。 | 户外、零售、汽车 |

## 故事板

| 图形模板 | 描述 | [!BADGE 用例]{type=Informative tooltip="使用案例"} |
|---|---|---|
| [**向故事板发送文本**](/help/firefly/graph/templates/text-to-storyboard.md) | 在此图表模板中，文本输入节点将替换为文章中的元素。 每行都将成为其自己的故事板框架，并作为单个面板集按顺序生成和排列以供审阅。 | 金融、零售、科技 |
| [**故事板生成器**](/help/firefly/graph/templates/storyboard-builder.md) | 在此图表模板中，您可以按场景构建故事板场景，每个叙述节拍添加一个节点。 在锁定最终面板顺序之前，请重新排序节点以测试不同的序列。 | 通信与电信、饮料、旅行 |

## 3D和字符

| 图形模板 | 描述 | [!BADGE 用例]{type=Informative tooltip="使用案例"} |
|---|---|---|
| [**实时着色器**](/help/firefly/graph/templates/real-time-shaders.md) | 在此图表模板中，您从一个图像开始应用三个不同的自定义着色器并实时预览结果。 直接在节点上调整着色器参数，而不是从头开始重新渲染。 | 技术、汽车、零售 |
| [**字符模型生成**](/help/firefly/graph/templates/character-model-generation.md) | 在此图表模板中，您将创建插图的3D动画样式。 模板将生成一个基础3D模型传递，此模型传递已准备好交给建模器清理，而不是从空白场景开始。 | 户外、科技、教育 |
| [**乙烯基玩具设计**](/help/firefly/graph/templates/vinyl-toy-design.md) | 在此图表模板中，您可以输入角色或吉祥物参考，并将其渲染为风格化的乙烯基玩具形式。 许可或产品审查幻灯片组有多种变通方法。 | 零售、饮料、娱乐 |
| [**素描到3D转折**](/help/firefly/graph/templates/sketch-to-3d.md) | 在此图表模板中，您可以将草图转换为3D角色。 该图形从中构建旋转的3D转折，可在任何物理原型之前进行内部设计审阅。 | 科技、汽车、娱乐 |

## 产品和品牌模型

| 图形模板 | 描述 | [!BADGE 用例]{type=Informative tooltip="使用案例"} |
|---|---|---|
| [**品牌形象可视化**](/help/firefly/graph/templates/branding-visualization.md) | 在此图表模板中，了解如何在产品场景中可视化徽标或品牌。 输入品牌准则或徽标和调色板，图形一次性输出静态关键图稿和短动态通道，因此两种格式在视觉上保持一致。 | 科技、饮料、金融 |
| [**品牌产品模型**](/help/firefly/graph/templates/brand-product-mockup.md) | 在此图表模板中，了解如何在不同的场景中可视化您的产品。 您将产品渲染或照片放入模型节点，然后图形会将其置于完全品牌化的场景中，并且光照和阴影会自动与该场景匹配。 | 零售、饮料、科技 |
| [**编辑摄影**](/help/firefly/graph/templates/editorial-photoshoot.md) | 在此图表模板中，您可以装入模型参考并交换每个新外观的服装输入。 姿势和光照节点在整个场景中保持锁定状态，以获得一致的编辑感觉。 | 零售、美容、户外 |
| [**摄影工作室**](/help/firefly/graph/templates/photography-studio.md) | 在此图表模板中，您将产品渲染置于摄影室背景上，并调整光照，直到结果看起来像真实的工作室捕捉。 | 饮料、科技、零售 |
| [**对表面应用贴花**](/help/firefly/graph/templates/decal-to-surfaces.md) | 在此图表模板中，您将加载基本产品模型和贴花或徽标资源作为单独的输入。 模板将贴花包络到曲面几何上，使其正确跟随轮廓。 | 户外、汽车、零售 |

## 批处理与一致性操作

| 图形模板 | 描述 | [!BADGE 用例]{type=Informative tooltip="使用案例"} |
|---|---|---|
| [**设计系统生成器**](/help/firefly/graph/templates/design-system-generator.md) | 在此图表模板中，您将基于网站屏幕截图生成设计系统。 图形在单个批处理运行中生成一组匹配的图标、图案和布局组件。 | 科技、金融、通信与电信 |
| [**生成大头照**](/help/firefly/graph/templates/headshots-generation.md) | 在此图表模板中，您将协调一批公司大头照。 加载源照片，每人一个，图形一圈就规范化光照、背景和裁剪整个集。 | 科技、金融、医疗 |

返回[开始使用Firefly图形](https://experienceleague.adobe.com/zh-hans/docs/creative-cloud-enterprise-learn/cce-learning-hub/fireflyoverview/firefly-graph/overview-firefly-graph)。
# Imagine-Art产品设计文档

## 产品概述

### 产品介绍

**产品核心概念**：在创作中学习，在学习中创作，以风格迁移（AI图生图）赋能儿童艺术创作。

**产品应用场景**：低龄儿童低成本美术启蒙教育。

### 产品用户

需要美术启蒙教育的低龄儿童以及其家长/教育者。

### 用户需求

| 状态 | 用户故事                                                                                                   | 需求描述                                                                                                                                                                    | 优先级 | 评审 |
| ---- | ---------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ | ---- |
|      | 用户希望学习经典美术风格，希望可以将美术风格融入到自己的作品中，并希望学习如何一步步创造相关风格的美术作品 | 产品允许用户一次上传一张风格图与一张内容图，实现简笔画上色并让其具有风格图的显著特征；产品使用Paints-Undo进行最终作品的绘画推演，让用户更直观地学习如何创造经典美术风格作品 | P0     | 评审 |
|      | 用户希望可以创造自己独特的美术风格，为他人提供美术创造的参考与灵感，并提升自我影响力                       | 产品允许用户训练自己的美术风格，并将自己训练的美术风格作为风格图片，对其他的内容图进行风格迁移                                                                              | P0     | 评审 |
|      | 用户希望可以分享自己的作品，得到他人的喜欢和指导建议，也希望可以浏览他人创作的作品，得到启发               | 开发社区模块，允许用户有选择地将自己的作品上传至社区，所有用户可以共同浏览社区中的作品，实时进行艺术创作交流                                                                | P0     | 评审 |
|      | 用户对某一经典美术风格很感兴趣，想多一些了解，但是又觉得上网查询很麻烦                                     | 在社区模块，由官方（开发者）上传经典美术风格的相关介绍，语言通俗易懂，由风格代表画家和代表作品，帮助用户及时学习，减少学习的时间成本                                        | P1     | 评审 |

## 主要功能模块

Imagine-Art产品主要包含以下核心模块：

1. [AI绘图模块](./ai-drawing.md) - **核心功能**，提供风格迁移和创作体验
2. [作品管理模块](./artwork-management.md) - 管理用户创作的作品
3. [社区分享模块](./modules.md#社区分享模块) - 分享和交流作品
4. [注册登录模块](./modules.md#注册登录模块) - 用户身份管理
5. [用户信息管理模块](./modules.md#用户信息管理模块) - 个人信息与通知管理

## 名词解释

- **风格图**：一张用来展示特定的艺术风格，比如颜色、纹理、笔触和光影效果等的图片，它提供了生成图像时需要"借鉴"的视觉美学。
- **内容图**：一张包含了主要的结构、形状和构图信息的图片，比如物体的位置、轮廓和细节等。它决定了图像的基本"内容"。
- **重绘**：利用AI模型对原图进行再创作。
- **视频推演**：对最终图像的生成过程进行推理，以视频的方式展示整个绘画过程。

## 路线图与规划

详见[功能路线图](./feature-roadmap.md)文档。

## 用户流程

详见[用户流程](./user-flow.md)文档。

## 模块详细说明

详细的模块划分与功能说明请参考：

- [AI绘图模块](./ai-drawing.md)（重点）
- [作品管理模块](./artwork-management.md)（重点）
- 其它模块请参考[模块拆分文档](./modules.md)

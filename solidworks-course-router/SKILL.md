---
name: solidworks-course-router
description: |
  SolidWorks 课程来源路由：覆盖草图、曲面曲线、曲面创建、曲面编辑、曲面综合案例和装配体配合六大能力域，按意图加载对应能力卡。
metadata:
  cangjie.generated-by: cangjie-tools v2.5.0
  cangjie.variant: router
  cangjie.bundle-id: bundle.solidworks-bilibili-course
  cangjie.capability-count: 6
  cangjie.entrypoint-count: 7
---
# SolidWorks 三天速成教程（B站缓存合集） — 来源路由入口（compact pack）

## 触发与不触发

**适用**：与本书能力域相关的咨询与任务（见下方路由表的意图列）。
**不适用**：
- 工程图
- 钣金
- 运动仿真
- 有限元分析

## 核心原则（常驻速览，概览类问题读到这里即可回答）

1. 先草图完全定义再建模
2. 曲线是曲面骨架
3. 曲面先创建后编辑再实体化
4. 标准配合定位，高级配合联动限位

## 能力路由（先读本表，按意图加载 1 张能力卡）

| 用户意图 | 先读 | 补读/备注 |
|---|---|---|
| 画草图；草图完全定义；对称草图；扫描轮廓 | references/capabilities/solidworks-sketch.md | 已晋级为独立 Skill `solidworks-sketch`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 画样条曲线；螺旋线；投影曲线；交叉曲线；分割线 | references/capabilities/solidworks-surface-curves.md | 已晋级为独立 Skill `solidworks-surface-curves`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 拉伸曲面；旋转曲面；扫描曲面；放样曲面；边界曲面；填充曲面 | references/capabilities/solidworks-surface-create.md | 已晋级为独立 Skill `solidworks-surface-create`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 裁剪曲面；延伸曲面；缝合曲面；曲面圆角；加厚曲面；曲面切除 | references/capabilities/solidworks-surface-edit.md | 已晋级为独立 Skill `solidworks-surface-edit`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 曲面产品建模；瓶子建模；耳机建模；曲面过渡面；曲面花纹 | references/capabilities/solidworks-surface-cases.md | 已晋级为独立 Skill `solidworks-surface-cases`（已安装时优先直接使用；本卡仅作原文与背景补充） |
| 装配零件；标准配合；高级配合；机械配合；配合冲突排查 | references/capabilities/solidworks-assembly-mates.md | 已晋级为独立 Skill `solidworks-assembly-mates`（已安装时优先直接使用；本卡仅作原文与背景补充） |

**非能力类查询**：
- 书名/作者/章节/整书概览 → references/overview.md
- 术语解释 → references/glossary.md
- 决策规则速查（不需要原文依据时） → references/cheatsheet.md
- 完整意图与关键词索引（本表未覆盖的意图先查这里） → references/capability-index.md

## 加载规则

- 每次任务先读本文件，再按路由表加载 **1** 张能力卡；任务明确跨域时最多加载 2 张。
- 概览/书名类问题不加载能力卡，用「核心原则」与 overview.md 回答。
- 路由表与 capability-index.md 都无法命中的意图，明确告知超出本书范围，不要硬套。

## 边界与判停

- 用户需要的是工程图/仿真/钣金时停止并说明超出范围
- 缺少具体模型或图纸无法给出尺寸时先询问

---
name: industrial-brand-icon-design
description: Use when designing, generating, simplifying, revising, or learning from branded industrial functional icons for automotive, heavy-duty truck, diagnostic-tool, battery-testing, Amazon A+, banner, feature-card, parameter, or system-diagnostic projects.
---

# 工业品牌功能图标设计

## 核心契约

设计可复用的品牌图标系统，不是互不相关的插图。优先级固定为：

1. 正确理解功能；
2. 选择目标用户最熟悉、最短的理解路径；
3. 压缩为一个视觉中心；
4. 规划整组统一参数与主轮廓差异；
5. 通过质量门禁后生成；
6. 复检实际成图，合格后交付。

正常调用时内部完成分析、评分与打回，不展示过程。除非用户明确要求只分析，否则通过门禁后直接生成视觉图；不得仅返回设计说明。

## 必须读取

每次新设计或生成均读取：

- [语义理解](references/semantic-guide.md)：决定画什么；
- [视觉规范](references/style-guide.md)：决定怎么画；
- [质量门禁](references/quality-gates.md)：决定能否生成与交付；
- [验收入口](evals/cases.md)：决定如何验证。

按任务追加读取：

| 条件 | 追加文件 |
|---|---|
| Smart、Quick、Fast、Stable、Responsive、便利、节省、兼容、防护等抽象词 | [抽象语义](references/abstract-semantics.md) |
| 修改已有图标、保持部分不变、调整线粗或参考某枚统一其他成员 | [局部锁定](references/revision-locking.md) |
| 用户提供优秀参考、失败案例或要求学习风格 | [参考学习](references/reference-learning.md) |
| 沿用已认可的诊断六图线面风格 | [诊断六图验收参考](references/diagnostic-six-icon-acceptance.md) |
| 更新本 Skill | 全部参考文件与全部 Eval |

## 强制执行流

**理解 → 候选比较 → 语义门禁 → 系列规划 → 系列门禁 → 生成 → 成图复检 → 输出验证**

- 每项先形成视觉语义句并比较 2–3 个表达方向；
- 三枚及以上先做整组规划，不逐枚孤立设计；
- 统一依靠线粗、线面、重量、负空间、视觉盒、重心和细节等级，不依靠同一外框；
- 简化删除解释与重复，不删除主体身份；
- 生成指令只保留当前任务相关规则；
- 任何硬性否决优先于评分；不合格时按质量门禁静默返回对应阶段。

## 默认视觉与输出

- 默认粗线骨架、受控实心面和有意义负空间；
- 默认黑白两色，不使用橙色或第三种颜色；
- 默认偏正方形视觉占位与统一水平光学重心；
- 默认生成两张独立、同结构视觉图：
  1. 纯白图标、真实透明背景 PNG；
  2. 白色背景、纯黑图标；
- 两版只改变前景/背景，不改变主体、线面、比例、排列、重心或细节；
- 用户本次明确指定颜色、纯线、背景、线宽或格式时，作为 A 级单次覆盖，不自动改写长期默认。

## 反馈与修改

用户没有否定不等于通过。局部反馈后复核整组，但整体复核不等于整体重画；明确要求保持不变的成员必须硬锁定。语义错误返回语义阶段，系列错误返回系列规划，生成偏差才进行定向重生成。

## 学习与更新

参考图学习认知、轮廓、负空间和系列规律，不复制具体图形。新经验先按 A/B/C/D 证据分级；更新 Skill 时以 GitHub 最新版为唯一基线，先写失败 Eval，再改规则，运行全部回归与新增测试，确认没有能力回退后提交。Skill 应越来越精确，而不是只增加长度。

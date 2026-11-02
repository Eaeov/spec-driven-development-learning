# Specification-Driven Development Learning

规范驱动开发（Specification-Driven Development，SDD）的个人学习记录，包含学习笔记、开发提示词、流程整理和可视化资料。

## 仓库内容

- [`SDD开发提示词.md`](./SDD开发提示词.md)：从项目上下文盘点、需求澄清到规范、实施、验证和反馈的提示词模板。
- [`开发流程.txt`](./开发流程.txt)：SDD 四阶段开发流程的简要整理。
- [`开发流程.png`](./开发流程.png)：SDD 开发流程图。
- [`九条原则.png`](./九条原则.png)：SDD 九条原则的学习图示。

## 推荐学习流程

```text
项目上下文盘点
  → 原始需求
  → 需求澄清
  → 生成可验证规范
  → 审查并简化规范
  → 制定实施计划
  → 按规范实现
  → 独立验证
  → 收集反馈并更新规范
```

## 使用方式

1. 从 `SDD开发提示词.md` 的“项目上下文自动盘点”开始。
2. 将 AI 发现的信息区分为“已确认、合理推断、未知”。
3. 在关键业务问题确认之前，不让 AI 直接编写代码。
4. 先写验收标准和测试，再进行最小范围实现。
5. 用户反馈改变预期行为时，同步更新规范、测试和代码。

## 参考资料

学习过程中参考了以下公开项目，第三方项目源码未包含在本仓库中：

- [Spec Driven Development QuickStart](https://github.com/Coldplay-now/Spec_driven_development_QuickStart)
- [GitHub Spec Kit](https://github.com/github/spec-kit)

本仓库内容会随着学习和实践持续完善。

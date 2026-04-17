# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.3.0] - 2026-04-30

### Added
- **发布准备内容**
  - 免责声明（法律声明、AI辅助生成声明、引用说明）
  - CC BY 4.0 开源许可证
  - "如何使用本文档"指南（针对不同角色的阅读路径）
  - CITATION.cff 学术引用文件
  - 独立模板文件（需求表单、门禁卡、变更记录）

### Changed
- 完善README.md，增强项目可读性

## [1.2.0] - 2026-04-30

### Added
- **模型评估指标与业务目标对齐**
  - 技术指标到业务价值映射表
  - 帮助非技术干系人理解指标意义
- **数据隐私脱敏与模型性能权衡说明**
  - 脱敏对模型性能的潜在影响分析
  - 脱敏前后模型性能对比实验要求
- **数据/模型变更快速决策树**
  - 4类变更场景的决策流程
  - 配套检查项
- **硬性规则豁免流程**
  - 豁免申请模板
  - 紧急情况下的规范流程

## [1.1.0] - 2026-04-22

### Added
- **标准框架更新**
  - 修正CPMAI六阶段理解（Business Understanding → Data Understanding → Data Preparation → Model Development → Model Evaluation → Model Operationalization）
  - 新增2026年最新标准引用：
    - 中国信通院《智能原生软件工程 研发智能化能力成熟度模型》
    - ISO/IEC NP 26044 生成式AI工具能力参考模型
    - 浙江省《人工智能标准化建设指南（2026版）》
    - T/TAF 320—2025《大型语言模型管理指南》
    - GB/T 45654—2025《生成式人工智能服务安全基本要求》
- **数据管理专章**（第三部分）
  - 数据需求分析（来源、格式、标注要求）
  - 数据准备阶段（清洗、特征工程）
  - 数据版本管理（DVC规范）
  - 数据质量门禁（检查清单、自动化脚本）
  - 数据隐私与合规审查（脱敏规范）
- **AI代码安全审计强化**
  - SAST扫描强制要求
  - Prompt注入风险检查
  - 安全规约驱动开发模式
  - 安全门禁指标（目标≥80%）
- **模型评估与管理章节**
  - 模型性能评估指标
  - A/B测试与模型对比
  - 模型漂移监控
  - 模型可解释性要求
  - 模型版本管理与回滚
- **扣子平台适配附录**
  - 平台资源模型
  - 需求表单与扣子定义映射
  - 工作流节点设计规范
  - 门禁检查项
  - 发布渠道对接

### Changed
- 目录结构调整，新增数据管理专章
- 章节编号相应调整

## [1.0.0] - 2026-04-17

### Added
- **项目管理总纲**
  - 六阶段模型（项目启动→方案设计→开发实现→测试验收→上线部署→运维迭代）
  - 门禁机制
  - 八条硬性规则
- **需求管理规范**
  - 需求门禁机制
  - 需求表单模板
  - 需求分级标准（P0-P3）
  - 场景闭环验证
  - 实战踩坑案例库
- **开发技术规范**
  - 代码规范
  - 测试规范
  - 安全规范
  - 部署规范
- **项目阶段规范**
  - 项目启动管理
  - 测试管理
  - 部署管理
  - 运维管理
  - 变更管理
  - 结构管理
- **快速参考**
  - 项目启动检查清单
  - 门禁卡模板
  - 快速问答

[1.3.0]: https://github.com/muwei-hub/ai-project-management-specification/compare/v1.2.0...v1.3.0
[1.2.0]: https://github.com/muwei-hub/ai-project-management-specification/compare/v1.1.0...v1.2.0
[1.1.0]: https://github.com/muwei-hub/ai-project-management-specification/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/muwei-hub/ai-project-management-specification/releases/tag/v1.0.0

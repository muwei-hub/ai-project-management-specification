# AI项目管理规范完整版

> **一句话说清**：一套让AI协作开发变得可控、可追溯、可交付的项目管理规范

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Version](https://img.shields.io/badge/Version-1.3-blue.svg)](https://github.com/muwei-hub/ai-project-management-specification/releases)
[![Status](https://img.shields.io/badge/Status-Active-success.svg)](https://github.com/muwei-hub/ai-project-management-specification)
[![GitHub stars](https://img.shields.io/github/stars/muwei-hub/ai-project-management-specification.svg)](https://github.com/muwei-hub/ai-project-management-specification/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/muwei-hub/ai-project-management-specification.svg)](https://github.com/muwei-hub/ai-project-management-specification/network)

**[English](docs/en/AI_Project_Management_Specification.md)** | **中文文档**

---

## 📖 项目简介

这是一个**编码小白**在AI协作编程过程中踩坑总结的项目管理规范。

结合PMI CPMAI、MLOps、ISO 42001等框架，把踩过的坑变成硬性规则，让AI协作开发变得可控、可追溯、可交付。

**核心价值：**
- 🚪 **门禁驱动** - 每个阶段必须通过检查才能进入下一阶段
- 📋 **八条硬性规则** - 没有需求文档不编码，改动先改文档再改代码
- 📊 **数据管理专章** - AI项目特有的数据需求、质量门禁、隐私合规
- 🔍 **模型评估体系** - 性能指标、漂移监控、版本管理
- 🛠 **实战踩坑案例** - 语法错误、硬编码、裸except...附正确写法

## 🚀 快速开始

### 在你的项目中使用

1. **新项目启动**
   ```bash
   # 下载模板
   git clone https://github.com/muwei-hub/ai-project-management-specification.git
   ```
2. **填写需求表单** - 使用 `模板/模板_需求表单.md`
3. **通过需求门禁** - 获得确认签字后，进入开发阶段
4. **使用门禁卡** - 每个阶段结束，用 `模板/模板_门禁卡.md` 检查

### 核心模板
| 模板 | 用途 |
|------|------|
| [需求表单](模板/模板_需求表单.md) | 项目启动时填写 |
| [门禁卡](模板/模板_门禁卡.md) | 各阶段质量检查 |
| [变更记录](模板/模板_变更记录.md) | 变更管理追踪 |

## 📚 文档结构

```
Part 1: 总纲              → 框架、原则、门禁机制
Part 2: 需求管理规范       → 需求表单、分级、验证
Part 3: 数据管理规范       → 数据需求、准备、质量门禁（AI项目特有）
Part 4: 开发技术规范       → 代码、测试、安全、部署
Part 5: 项目阶段规范       → 启动、测试、部署、运维、变更
Part 6: 快速参考          → 检查清单、门禁卡、快速问答
Appendix                  → 文档索引、版本历史、扣子平台适配
```

📖 **完整文档**：[AI项目管理规范完整版.md](docs/AI项目管理规范完整版.md)

## 🤝 如何贡献

欢迎参与改进这份规范！

### 贡献方式
- 📝 **提交Issue** - 报告问题、提出建议、分享使用经验
- 🔧 **Pull Request** - 修复错误、补充内容、优化文档
- 💬 **Discussions** - 参与讨论，帮助其他用户

### 贡献流程
1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/your-feature`)
3. 提交更改 (`git commit -m 'Add some feature'`)
4. 推送到分支 (`git push origin feature/your-feature`)
5. 创建 Pull Request

### 贡献指南
- 保持文档风格一致
- 新增内容需有实际可操作性
- 引用数据需标注来源

## 📜 许可证与引用

### 许可证
本作品采用 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) 许可证发布。您可以自由地分享和演绎，惟须署名。

### 学术引用
如果您在学术论文中引用本规范，请使用以下格式：

```bibtex
@misc{ai-pm-spec,
  author = {Muwei},
  title = {AI Project Management Specification},
  year = {2026},
  publisher = {GitHub},
  url = {https://github.com/muwei-hub/ai-project-management-specification}
}
```

或直接使用仓库中的 [CITATION.cff](CITATION.cff) 文件。

## 🔗 参考框架

| 来源 | 核心贡献 |
|------|----------|
| PMI CPMAI | AI项目管理六阶段方法论 |
| MLOps | 数据-模型-代码一体化管理 |
| ISO 42001 | AI管理体系国际标准 |
| Google MLOps | 成熟度模型渐进式演进 |
| 中国信通院 | 智能原生软件工程成熟度模型 |
| ISO/IEC NP 26044 | 生成式AI工具能力参考模型 |

---

**如果这份规范对你有帮助，欢迎 ⭐ Star 支持！**

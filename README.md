# ProClaw-Partner-insight.skill | 人生伴侣分析技能.skill

[中文](#chinese) |  [English](#english) 

---

<a name="chinese"></a>
## 中文

### 概览
ProClaw-Partner-insight 是一个强大的伴侣洞察工具，用于识别伴侣的人格格局类型（丫鬟型、妃子型、皇后型），分析行为信号，检测常见误判点，并提供关系影响评估和决策建议。

### 核心功能

#### 三种格局类型
- **丫鬟型**: 勤恳务实，注重细节，执行力强，但缺乏战略视野
- **妃子型**: 精致追求，注重形象和认可，容易出现内部矛盾
- **皇后型**: 战略思维，全局视野，领导力强，真正的战略伙伴

#### 能力体系
- **格局识别**: 通过行为信号识别伴侣的格局类型
- **风险评估**: 评估关系风险和潜在影响
- **误判检测**: 检测常见判断错误和偏见
- **决策支持**: 为关系决策提供可操作的建议

### 使用场景

#### 场景1：判断关系模式
**场景**: 用户想了解伴侣的人格格局类型

**使用方法**:
```bash
# 评估伴侣格局
python scripts/assess_partner.py \
  --supportiveness 8 \
  --strategic_thinking 3 \
  --execution 9 \
  --independence 4 \
  --conflict_resolution 5 \
  --growth_potential 3
```

**预期输出**:
```json
{
  "pattern": "丫鬟型",
  "risk_level": "中危",
  "impact": "可能拖累事业发展",
  "recommendations": ["培养独立思考能力", "逐步增加决策责任"]
}
```

#### 场景2：扫描关系风险
**场景**: 用户想识别关系中的潜在风险

**使用方法**:
```bash
# 扫描风险
python scripts/scan_risk.py \
  --over_dependence 8 \
  --emotional_manipulation 3 \
  --value_conflict 4 \
  --communication_block 2
```

#### 场景3：分析混合特征
**场景**: 用户的伴侣表现出混合特征

**使用方法**:
```bash
# 分析混合格局
python scripts/analyze_hybrid.py \
  --maid_score 7 \
  --concubine_score 6 \
  --empress_score 4
```

### 技能结构

```
ProClaw-Partner-insight/
├── SKILL.md                    # 主入口和指南
├── scripts/                    # 可执行工具
│   ├── assess_partner.py      # 格局评估
│   ├── scan_risk.py           # 风险扫描
│   ├── analyze_hybrid.py      # 混合格局分析
│   └── support_decision.py    # 决策支持
├── references/                 # 参考文档
│   ├── assessment-model.md    # 评估模型
│   ├── decision-tree.md       # 决策树
│   ├── tracking-framework.md  # 跟踪框架
│   ├── hybrid-identifier.md   # 混合特征识别器
│   ├── risk-warning-system.md # 风险预警系统
│   └── decision-matrix.md     # 决策矩阵
└── assets/                    # 资源
    ├── templates/             # 模板
    ├── tables/                # 表格和清单
    └── faq/                   # 常见问题
```

### 作者信息
- **作者**: ProClaw
- **网站**: www.proclaw.top
- **联系方式**: wechat:Mr-zifang
- **版本**: 1.1

### 版本历史
- **v1.1** (2025-04-25): 增加作者信息，重命名为 ProClaw-Partner-insight
- **v1.0** (2025-04-25): 初始发布，完整的格局识别系统
---

<a name="english"></a>
## English

### Overview
ProClaw-Partner-insight is a powerful skill for identifying partner personality patterns (Maid Type, Concubine Type, Empress Type), analyzing behavioral signals, detecting common misconceptions, and providing relationship impact assessments and decision-making support.

### Features

#### Three Pattern Types
- **Maid Type (丫鬟型)**: Diligent and practical,注重细节, strong execution, but lacks strategic vision
- **Concubine Type (妃子型)**: Refined and competitive,追求形象和认可, prone to internal conflicts
- **Empress Type (皇后型)**: Strategic thinking, global vision, strong leadership, true strategic partner

#### Core Capabilities
- **Pattern Identification**: Identify partner's personality pattern through behavioral signals
- **Risk Assessment**: Evaluate relationship risks and potential impacts
- **Misconception Detection**: Detect common judgment errors and biases
- **Decision Support**: Provide actionable recommendations for relationship decisions

### Use Cases

#### Case 1: Determine Relationship Pattern
**Scenario**: User wants to understand their partner's personality pattern

**Usage**:
```bash
# Assess partner pattern
python scripts/assess_partner.py \
  --supportiveness 8 \
  --strategic_thinking 3 \
  --execution 9 \
  --independence 4 \
  --conflict_resolution 5 \
  --growth_potential 3
```

**Expected Output**:
```json
{
  "pattern": "丫鬟型 (Maid Type)",
  "risk_level": "中危 (Medium Risk)",
  "impact": "可能拖累事业发展 (May hinder career development)",
  "recommendations": ["培养独立思考能力", "逐步增加决策责任"]
}
```

#### Case 2: Scan Relationship Risks
**Scenario**: User wants to identify potential risks in their relationship

**Usage**:
```bash
# Scan risks
python scripts/scan_risk.py \
  --over_dependence 8 \
  --emotional_manipulation 3 \
  --value_conflict 4 \
  --communication_block 2
```

#### Case 3: Analyze Hybrid Features
**Scenario**: User's partner shows mixed characteristics

**Usage**:
```bash
# Analyze hybrid patterns
python scripts/analyze_hybrid.py \
  --maid_score 7 \
  --concubine_score 6 \
  --empress_score 4
```

### Skill Structure

```
ProClaw-Partner-insight/
├── SKILL.md                    # Main entry and guide
├── scripts/                    # Executable tools
│   ├── assess_partner.py      # Pattern assessment
│   ├── scan_risk.py           # Risk scanning
│   ├── analyze_hybrid.py      # Hybrid pattern analysis
│   └── support_decision.py    # Decision support
├── references/                 # Reference documents
│   ├── assessment-model.md    # Assessment model
│   ├── decision-tree.md       # Decision tree
│   ├── tracking-framework.md  # Tracking framework
│   ├── hybrid-identifier.md   # Hybrid identifier
│   ├── risk-warning-system.md # Risk warning system
│   └── decision-matrix.md     # Decision matrix
└── assets/                    # Resources
    ├── templates/             # Templates
    ├── tables/                # Tables and checklists
    └── faq/                   # FAQ
```

### Author Information
- **Author**: ProClaw
- **Website**: www.proclaw.top
- **Contact**: wechat:Mr-zifang
- **Version**: 1.1

### Version History
- **v1.1** (2025-04-25): Added author information, renamed to ProClaw-Partner-insight
- **v1.0** (2025-04-25): Initial release with complete pattern identification system

### 快速开始

#### 安装
```bash
# 解压 .skill 文件
# 进入技能目录
cd ProClaw-Partner-insight
```

#### 基础使用
```bash
# 评估伴侣格局
python scripts/assess_partner.py --supportiveness 8 --strategic_thinking 3 --execution 9 --independence 4 --conflict_resolution 5 --growth_potential 3

# 扫描关系风险
python scripts/scan_risk.py --over_dependence 8 --emotional_manipulation 3 --value_conflict 4 --communication_block 2

# 分析混合特征
python scripts/analyze_hybrid.py --maid_score 7 --concubine_score 6 --empress_score 4

# 决策支持
python scripts/support_decision.py --impact_score 6 --risk_level 3 --growth_potential 4 --relationship_quality 7
```

### 常见问题

#### Q: 如何确定我的伴侣属于哪种格局类型？
A: 使用 `assess_partner.py` 工具，根据6个维度的评分进行评估。工具会给出格局类型、风险等级和改进建议。

#### Q: 什么是混合特征？
A: 混合特征是指一个人同时表现出多种格局类型的特征。使用 `analyze_hybrid.py` 工具可以分析混合特征并预测长期趋势。

#### Q: 如何判断关系是否健康？
A: 使用 `scan_risk.py` 工具扫描关系中的危险信号，评估风险等级。低风险表示关系健康，高风险表示需要关注。

#### Q: 这个工具适合什么人群？
A: 适合所有想要深入了解伴侣关系、优化关系质量的人群，特别是处于重要关系决策阶段的人。

### 技术支持
- **网站**: www.proclaw.top
- **微信**: Mr-zifong
- **邮箱**: [通过微信联系]

### 许可证
本技能由 ProClaw 开发和维护。

### 致谢
感谢所有提供反馈和建议的用户。

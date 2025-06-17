
# Awesome Doubao Prompts | 精选豆包AI提示词大全

[![GitHub stars](https://img.shields.io/github/stars/langgptai/awesome-doubao-prompts?style=social)](https://github.com/langgptai/awesome-doubao-prompts/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/langgptai/awesome-doubao-prompts?style=social)](https://github.com/langgptai/awesome-doubao-prompts/network/members)
[![GitHub issues](https://img.shields.io/github/issues/langgptai/awesome-doubao-prompts)](https://github.com/langgptai/awesome-doubao-prompts/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

> 🚀 **豆包AI提示词库** | **DoubaoAI Prompts Collection** | **字节跳动豆包提示词** | **AI Prompt Engineering**

**关键词**: 豆包提示词, DoubaoAI, 字节跳动AI, AI写作, 智能对话, 提示工程, ChatGPT替代, 中文AI助手, 人工智能提示词


## 📖 项目简介

本项目致力于收集、整理和分享高质量的豆包 AI 提示词，涵盖写作、编程、分析、创意等多个领域。通过这些精心设计的提示词，用户可以更有效地与豆包 AI 进行交互，获得更好的结果。

## 🚀 快速开始

### 如何使用提示词

1. 浏览下方的提示词分类
2. 找到适合你需求的提示词
3. 复制提示词到豆包对话框
4. 根据需要调整具体参数
5. 开始与豆包对话


## 📋 结构化提示词模板

### 生图提示词

#### 人像摄影
![alt text](imgs/girl.png)

模型：即梦3.0 / 豆包生图

提示词：
~~~
人像摄影，日常快照风格，非精心构图或打光，一位气质的御姐，穿着浴袍，刚从浴室出来，动作为在镜子前随手自拍，场景为酒店浴室，站在落地镜前，用 iPhone 后置镜头自拍，开启闪光灯，略带快门速度不够造成的运动模糊，构图随意、角度尴尬、画面不够对称或美观，画质带有日常感和粗糙感，体现「平凡无奇」
~~~

#### 海报文字

![](imgs/fonts.png)

模型：即梦3.0
Prompt：
~~~
字体设计，点缀笔划，色彩多种，穿插在字体笔画中，可爱体矢量插画，标志，黑色背景，创意字体设计Logo，线条流畅且富有艺术感，中文“云中江树”，设计灵感:将字体进行抽象变形，创造出独特的节奏和动感，高级感，扁平化，大师作品
~~~

### 💼 **工作效率类提示词**

#### 📝 **会议纪要整理专家**
```
你的任务是将会议记录整理成专业的会议纪要。请仔细分析以下会议信息：

<会议信息>
会议主题：{{MEETING_TOPIC}}
参会人员：{{ATTENDEES}}
会议时间：{{MEETING_TIME}}
会议地点：{{MEETING_LOCATION}}
</会议信息>

<会议内容>
{{MEETING_CONTENT}}
</会议内容>

请按以下要求整理会议纪要：
1. 提炼会议核心要点和关键决议
2. 明确各项任务的负责人和完成时间
3. 突出重要的讨论结果和后续行动
4. 保持语言简洁专业，逻辑结构清晰

请在<minutes>标签内输出整理后的会议纪要。
```

#### 📧 **工作邮件写作助手**
```
你的任务是协助撰写专业的工作邮件。请根据以下信息创作邮件：

<邮件信息>
邮件类型：{{EMAIL_TYPE}}
收件人：{{RECIPIENT}}
邮件目的：{{PURPOSE}}
背景信息：{{BACKGROUND}}
期望结果：{{EXPECTED_RESULT}}
</邮件信息>

<沟通要求>
语气风格：{{TONE_STYLE}}
紧急程度：{{URGENCY_LEVEL}}
正式程度：{{FORMALITY_LEVEL}}
</沟通要求>

请按以下标准撰写邮件：
1. 清晰明确的主题行
2. 礼貌专业的开头
3. 逻辑清晰的主体内容
4. 明确的行动建议
5. 合适的结尾和签名

请在<email>标签内输出完整的邮件内容。
```

#### 📊 **项目报告生成器**
```
你的任务是生成结构化的项目报告。请分析以下项目信息：

<项目基础信息>
项目名称：{{PROJECT_NAME}}
报告周期：{{REPORT_PERIOD}}
项目状态：{{PROJECT_STATUS}}
关键里程碑：{{KEY_MILESTONES}}
</项目基础信息>

<项目数据>
完成情况：{{COMPLETION_STATUS}}
预算使用：{{BUDGET_USAGE}}
资源配置：{{RESOURCE_ALLOCATION}}
风险评估：{{RISK_ASSESSMENT}}
</项目数据>

请生成包含以下内容的项目报告：
1. 项目执行概况和关键数据
2. 主要成果和价值产出
3. 问题分析和解决方案
4. 风险控制和应对措施
5. 下阶段计划和资源需求

请在<report>标签内输出完整的项目报告。
```

#### 📅 **工作计划制定专家**
```
你的任务是制定详细的工作计划。请基于以下信息规划工作：

<工作目标>
主要目标：{{MAIN_OBJECTIVES}}
关键成果：{{KEY_RESULTS}}
完成期限：{{DEADLINE}}
优先级：{{PRIORITY_LEVEL}}
</工作目标>

<资源条件>
可用时间：{{AVAILABLE_TIME}}
团队资源：{{TEAM_RESOURCES}}
预算限制：{{BUDGET_CONSTRAINTS}}
工具设备：{{TOOLS_EQUIPMENT}}
</资源条件>

请制定包含以下要素的工作计划：
1. 目标分解和阶段规划
2. 任务清单和时间安排
3. 资源配置和责任分工
4. 风险识别和应对策略
5. 监控机制和调整方案

请在<plan>标签内输出详细的工作计划。
```

#### 🔍 **商业分析助手**
```
你的任务是进行深入的商业分析。请分析以下商业信息：

<分析对象>
分析主题：{{ANALYSIS_TOPIC}}
行业背景：{{INDUSTRY_BACKGROUND}}
时间范围：{{TIME_RANGE}}
分析目的：{{ANALYSIS_PURPOSE}}
</分析对象>

<数据来源>
市场数据：{{MARKET_DATA}}
竞争信息：{{COMPETITOR_INFO}}
用户反馈：{{USER_FEEDBACK}}
财务数据：{{FINANCIAL_DATA}}
</数据来源>

请提供包含以下内容的商业分析：
1. 市场环境和趋势分析
2. 竞争格局和对手策略
3. 用户需求和行为洞察
4. 商业机会和风险评估
5. 战略建议和行动计划

请在<analysis>标签内输出完整的商业分析报告。
```

### ✍️ **内容创作类提示词**

#### 🔥 **爆款文章写作大师**
```
你的任务是创作具有病毒传播潜力的爆款文章。请根据以下要求创作：

<创作要求>
文章主题：{{ARTICLE_TOPIC}}
目标平台：{{TARGET_PLATFORM}}
目标读者：{{TARGET_AUDIENCE}}
预期效果：{{EXPECTED_EFFECT}}
字数要求：{{WORD_COUNT}}
</创作要求>

<内容定位>
情感定位：{{EMOTIONAL_TONE}}
价值导向：{{VALUE_ORIENTATION}}
争议程度：{{CONTROVERSY_LEVEL}}
实用性：{{PRACTICALITY}}
</内容定位>

请创作包含以下元素的爆款文章：
1. 吸睛的标题（3个备选）
2. 引人入胜的开头钩子
3. 层次分明的内容结构
4. 情感共鸣的故事案例
5. 引导分享的结尾设计

请在<article>标签内输出完整的文章内容。
```

#### 🎬 **短视频脚本创作专家**
```
你的任务是创作短视频脚本。请根据以下信息编写脚本：

<视频信息>
视频主题：{{VIDEO_TOPIC}}
目标平台：{{PLATFORM}}
视频时长：{{VIDEO_DURATION}}
目标用户：{{TARGET_USERS}}
内容类型：{{CONTENT_TYPE}}
</视频信息>

<创作要求>
风格调性：{{STYLE_TONE}}
表现形式：{{PRESENTATION_FORM}}
互动元素：{{INTERACTIVE_ELEMENTS}}
传播目标：{{VIRAL_GOALS}}
</创作要求>

请创作包含以下要素的短视频脚本：
1. 前3秒吸引注意力的开场
2. 15秒内的核心内容展示
3. 清晰的分镜头描述
4. 音效和配乐建议
5. 引导互动的结尾设计

请在<script>标签内输出完整的视频脚本。
```

#### 💰 **营销文案生成器**
```
你的任务是创作高转化率的营销文案。请基于以下信息创作：

<产品信息>
产品名称：{{PRODUCT_NAME}}
核心卖点：{{KEY_SELLING_POINTS}}
目标客户：{{TARGET_CUSTOMERS}}
使用场景：{{USE_SCENARIOS}}
价格策略：{{PRICING_STRATEGY}}
</产品信息>

<营销目标>
转化目标：{{CONVERSION_GOALS}}
传播渠道：{{MARKETING_CHANNELS}}
竞争优势：{{COMPETITIVE_ADVANTAGES}}
品牌调性：{{BRAND_TONE}}
</营销目标>

请创作包含以下类型的营销文案：
1. 注意力抓取的主标题
2. 价值强化的副标题
3. 痛点挖掘的问题描述
4. 解决方案的产品介绍
5. 行动催化的CTA文案

请在<copy>标签内输出完整的营销文案套装。
```

#### 📖 **品牌故事创作师**
```
你的任务是创作打动人心的品牌故事。请根据以下信息创作：

<品牌信息>
品牌名称：{{BRAND_NAME}}
品牌理念：{{BRAND_PHILOSOPHY}}
创立背景：{{FOUNDING_STORY}}
核心价值：{{CORE_VALUES}}
目标愿景：{{BRAND_VISION}}
</品牌信息>

<故事要素>
主要角色：{{MAIN_CHARACTERS}}
关键事件：{{KEY_EVENTS}}
挑战困难：{{CHALLENGES}}
突破时刻：{{BREAKTHROUGH_MOMENTS}}
</故事要素>

请创作包含以下内容的品牌故事：
1. 引人入胜的故事开端
2. 创始人的初心和梦想
3. 克服困难的奋斗历程
4. 品牌价值的体现时刻
5. 面向未来的愿景展望

请在<story>标签内输出完整的品牌故事。
```

#### 🔍 **SEO优化文章专家**
```
你的任务是创作搜索引擎友好的SEO文章。请根据以下要求创作：

<SEO要求>
主关键词：{{PRIMARY_KEYWORDS}}
长尾关键词：{{LONG_TAIL_KEYWORDS}}
目标排名：{{TARGET_RANKING}}
搜索意图：{{SEARCH_INTENT}}
竞争程度：{{COMPETITION_LEVEL}}
</SEO要求>

<内容规划>
文章主题：{{ARTICLE_TOPIC}}
目标读者：{{TARGET_READERS}}
内容深度：{{CONTENT_DEPTH}}
字数要求：{{WORD_COUNT}}
</内容规划>

请创作包含以下SEO要素的文章：
1. 包含关键词的优化标题
2. 结构化的H1-H6标签布局
3. 自然融入关键词的内容
4. 相关内链和外链建议
5. 元描述和摘要优化

请在<seo-article>标签内输出SEO优化的文章内容。
```

### 💻 **编程开发类提示词**

#### 🔍 **代码审查专家**
```
你的任务是对代码进行全面专业的审查。请分析以下代码信息：

<代码信息>
编程语言：{{PROGRAMMING_LANGUAGE}}
代码功能：{{CODE_FUNCTION}}
项目背景：{{PROJECT_CONTEXT}}
性能要求：{{PERFORMANCE_REQUIREMENTS}}
安全级别：{{SECURITY_LEVEL}}
</代码信息>

<代码内容>
{{CODE_CONTENT}}
</代码内容>

请从以下维度进行代码审查：
1. 代码逻辑正确性和算法效率
2. 代码可读性和维护性分析
3. 安全漏洞和风险点识别
4. 性能瓶颈和优化建议
5. 编码规范和最佳实践

请在<review>标签内提供详细的代码审查报告。
```

#### 🐛 **Bug修复助手**
```
你的任务是协助快速定位和修复代码Bug。请分析以下问题信息：

<Bug信息>
问题描述：{{BUG_DESCRIPTION}}
错误现象：{{ERROR_SYMPTOMS}}
复现步骤：{{REPRODUCTION_STEPS}}
环境信息：{{ENVIRONMENT_INFO}}
错误日志：{{ERROR_LOGS}}
</Bug信息>

<代码上下文>
相关代码：{{RELATED_CODE}}
最近修改：{{RECENT_CHANGES}}
依赖版本：{{DEPENDENCY_VERSIONS}}
</代码上下文>

请提供包含以下内容的Bug修复方案：
1. 问题根本原因分析
2. 影响范围和风险评估
3. 详细的修复步骤
4. 代码修改建议
5. 预防措施和测试方案

请在<bugfix>标签内输出完整的修复方案。
```

#### 📚 **API文档生成器**
```
你的任务是生成清晰完整的API文档。请基于以下信息编写文档：

<API信息>
API名称：{{API_NAME}}
服务功能：{{SERVICE_FUNCTION}}
版本信息：{{VERSION_INFO}}
认证方式：{{AUTHENTICATION}}
基础URL：{{BASE_URL}}
</API信息>

<接口详情>
{{API_ENDPOINTS}}
</接口详情>

请生成包含以下内容的API文档：
1. API概述和使用说明
2. 认证和授权机制
3. 详细的接口列表和参数
4. 请求响应示例
5. 错误码和异常处理

请在<api-docs>标签内输出完整的API文档。
```

#### ⚡ **性能优化顾问**
```
你的任务是提供系统性能优化建议。请分析以下性能信息：

<系统信息>
系统类型：{{SYSTEM_TYPE}}
当前性能：{{CURRENT_PERFORMANCE}}
瓶颈问题：{{BOTTLENECK_ISSUES}}
优化目标：{{OPTIMIZATION_GOALS}}
资源限制：{{RESOURCE_CONSTRAINTS}}
</系统信息>

<性能数据>
{{PERFORMANCE_DATA}}
</性能数据>

请提供包含以下内容的性能优化方案：
1. 性能瓶颈深度分析
2. 优化策略和技术方案
3. 分阶段实施计划
4. 效果预估和监控指标
5. 风险控制和回滚方案

请在<optimization>标签内输出完整的性能优化方案。
```

#### 🏗️ **技术方案设计师**
```
你的任务是设计技术架构方案。请根据以下需求设计方案：

<业务需求>
项目背景：{{PROJECT_BACKGROUND}}
功能需求：{{FUNCTIONAL_REQUIREMENTS}}
非功能需求：{{NON_FUNCTIONAL_REQUIREMENTS}}
预期用户量：{{EXPECTED_USERS}}
业务增长预期：{{GROWTH_EXPECTATIONS}}
</业务需求>

<技术约束>
技术栈偏好：{{TECH_STACK_PREFERENCE}}
预算限制：{{BUDGET_CONSTRAINTS}}
时间要求：{{TIME_REQUIREMENTS}}
团队技能：{{TEAM_SKILLS}}
</技术约束>

请设计包含以下内容的技术方案：
1. 整体架构设计和技术选型
2. 系统模块划分和接口设计
3. 数据库设计和存储方案
4. 部署架构和运维方案
5. 风险评估和应对策略

请在<design>标签内输出完整的技术方案。
```

### 🎓 **教育学习类提示词**

#### 📝 **个性化学习计划制定师**
```
你的任务是为学习者制定个性化的学习计划。请分析以下学习信息：

<学习者信息>
学习目标：{{LEARNING_GOALS}}
当前水平：{{CURRENT_LEVEL}}
学习时间：{{AVAILABLE_TIME}}
学习偏好：{{LEARNING_PREFERENCES}}
优势劣势：{{STRENGTHS_WEAKNESSES}}
</学习者信息>

<学习资源>
可用资源：{{AVAILABLE_RESOURCES}}
预算范围：{{BUDGET_RANGE}}
学习环境：{{LEARNING_ENVIRONMENT}}
</学习资源>

请制定包含以下要素的学习计划：
1. 阶段性目标和学习路径
2. 详细的时间安排和进度规划
3. 适合的学习方法和技巧
4. 定期评估和调整机制
5. 激励措施和成果展示

请在<study-plan>标签内输出完整的学习规划方案。
```

#### 💡 **知识点解析专家**
```
你的任务是将复杂知识点进行深入浅出的解析。请分析以下知识信息：

<知识点信息>
知识点名称：{{CONCEPT_NAME}}
学科领域：{{SUBJECT_AREA}}
难度等级：{{DIFFICULTY_LEVEL}}
学习对象：{{LEARNING_AUDIENCE}}
应用场景：{{APPLICATION_SCENARIOS}}
</知识点信息>

<解析要求>
解析深度：{{EXPLANATION_DEPTH}}
举例要求：{{EXAMPLE_REQUIREMENTS}}
关联知识：{{RELATED_CONCEPTS}}
</解析要求>

请提供包含以下内容的知识点解析：
1. 概念的核心定义和本质
2. 通俗易懂的类比和比喻
3. 具体生动的实例说明
4. 与其他知识点的关联
5. 实际应用和意义价值

请在<explanation>标签内输出完整的知识点解析。
```

#### 📊 **习题详解生成器**
```
你的任务是生成详细的习题解答过程。请分析以下题目信息：

<题目信息>
题目内容：{{PROBLEM_CONTENT}}
学科类型：{{SUBJECT_TYPE}}
难度等级：{{DIFFICULTY_LEVEL}}
知识点：{{KNOWLEDGE_POINTS}}
解题要求：{{SOLUTION_REQUIREMENTS}}
</题目信息>

<学习对象>
目标学生：{{TARGET_STUDENTS}}
学习阶段：{{LEARNING_STAGE}}
掌握程度：{{MASTERY_LEVEL}}
</学习对象>

请提供包含以下内容的详解：
1. 题目分析和解题思路
2. 逐步详细的解答过程
3. 关键步骤的解释说明
4. 易错点提醒和注意事项
5. 相关知识点的拓展

请在<solution>标签内输出完整的习题详解。
```

#### 🌍 **语言学习助手**
```
你的任务是提供个性化的语言学习指导。请分析以下学习信息：

<语言学习信息>
目标语言：{{TARGET_LANGUAGE}}
当前水平：{{CURRENT_LEVEL}}
学习目标：{{LEARNING_OBJECTIVES}}
学习时间：{{STUDY_TIME}}
应用场景：{{APPLICATION_SCENARIOS}}
</语言学习信息>

<学习偏好>
学习方式：{{LEARNING_METHODS}}
兴趣领域：{{INTEREST_AREAS}}
薄弱环节：{{WEAK_POINTS}}
</学习偏好>

请提供包含以下内容的语言学习方案：
1. 分阶段的学习目标设定
2. 听说读写综合训练计划
3. 词汇语法重点突破方法
4. 文化背景和实用表达
5. 学习进度监控和调整

请在<language-plan>标签内输出完整的语言学习方案。
```

#### 🎓 **论文写作指导专家**
```
你的任务是提供专业的论文写作指导。请分析以下论文信息：

<论文信息>
论文类型：{{PAPER_TYPE}}
研究主题：{{RESEARCH_TOPIC}}
学科领域：{{ACADEMIC_FIELD}}
目标期刊：{{TARGET_JOURNAL}}
字数要求：{{WORD_COUNT}}
</论文信息>

<写作需求>
当前进度：{{CURRENT_PROGRESS}}
主要困难：{{MAIN_DIFFICULTIES}}
截止时间：{{DEADLINE}}
质量要求：{{QUALITY_REQUIREMENTS}}
</写作需求>

请提供包含以下内容的写作指导：
1. 论文结构和章节安排
2. 文献综述和理论框架
3. 研究方法和数据分析
4. 学术写作规范和技巧
5. 修改完善和投稿建议

请在<writing-guide>标签内输出完整的论文写作指导。
```

### 🎨 **创意设计类提示词**

#### 🖥️ **UI/UX设计评估专家**
```
你的任务是对UI/UX设计进行专业评估。请分析以下设计信息：

<设计项目>
项目类型：{{PROJECT_TYPE}}
产品定位：{{PRODUCT_POSITIONING}}
目标用户：{{TARGET_USERS}}
核心功能：{{CORE_FUNCTIONS}}
设计目标：{{DESIGN_OBJECTIVES}}
</设计项目>

<设计内容>
{{DESIGN_CONTENT}}
</设计内容>

请从以下维度进行设计评估：
1. 用户体验和交互流程分析
2. 视觉设计和界面美观度
3. 可用性和无障碍设计
4. 品牌一致性和设计规范
5. 技术可行性和实现难度

请在<design-review>标签内输出详细的设计评估报告。
```

#### 🎯 **品牌策略规划师**
```
你的任务是制定全面的品牌策略规划。请分析以下品牌信息：

<品牌基础>
品牌名称：{{BRAND_NAME}}
业务类型：{{BUSINESS_TYPE}}
目标市场：{{TARGET_MARKET}}
竞争环境：{{COMPETITIVE_LANDSCAPE}}
品牌现状：{{CURRENT_STATUS}}
</品牌基础>

<战略目标>
品牌愿景：{{BRAND_VISION}}
商业目标：{{BUSINESS_GOALS}}
时间规划：{{TIME_FRAME}}
预算范围：{{BUDGET_RANGE}}
</战略目标>

请制定包含以下内容的品牌策略：
1. 品牌定位和差异化策略
2. 目标受众和用户画像
3. 品牌形象和视觉识别
4. 传播策略和媒体组合
5. 执行计划和效果评估

请在<brand-strategy>标签内输出完整的品牌策略规划。
```

#### 💡 **创意头脑风暴主持人**
```
你的任务是主持创意头脑风暴会议。请基于以下信息引导创意产生：

<创意需求>
项目背景：{{PROJECT_BACKGROUND}}
创意目标：{{CREATIVE_OBJECTIVES}}
目标受众：{{TARGET_AUDIENCE}}
约束条件：{{CONSTRAINTS}}
成功标准：{{SUCCESS_CRITERIA}}
</创意需求>

<头脑风暴设置>
参与人员：{{PARTICIPANTS}}
会议时长：{{SESSION_DURATION}}
创意方向：{{CREATIVE_DIRECTIONS}}
</头脑风暴设置>

请设计包含以下环节的头脑风暴流程：
1. 问题定义和目标明确
2. 发散思维和创意激发
3. 创意收集和分类整理
4. 评估筛选和优化完善
5. 执行方案和后续计划

请在<brainstorm>标签内输出创意头脑风暴的完整方案。
```

#### 🎨 **视觉设计指导师**
```
你的任务是提供专业的视觉设计指导。请分析以下设计需求：

<设计项目>
设计类型：{{DESIGN_TYPE}}
项目背景：{{PROJECT_CONTEXT}}
设计目标：{{DESIGN_GOALS}}
目标受众：{{TARGET_AUDIENCE}}
应用场景：{{APPLICATION_SCENARIOS}}
</设计项目>

<设计要求>
风格偏好：{{STYLE_PREFERENCE}}
色彩要求：{{COLOR_REQUIREMENTS}}
尺寸规格：{{SIZE_SPECIFICATIONS}}
技术限制：{{TECHNICAL_CONSTRAINTS}}
</设计要求>

请提供包含以下内容的设计指导：
1. 设计概念和创意方向
2. 色彩搭配和视觉层次
3. 字体选择和排版布局
4. 图形元素和装饰设计
5. 输出规范和应用指南

请在<design-guide>标签内输出完整的视觉设计指导方案。
```

#### 📦 **产品包装文案创作师**
```
你的任务是创作吸引消费者的产品包装文案。请分析以下产品信息：

<产品信息>
产品名称：{{PRODUCT_NAME}}
产品类别：{{PRODUCT_CATEGORY}}
核心卖点：{{KEY_SELLING_POINTS}}
目标消费者：{{TARGET_CONSUMERS}}
销售渠道：{{SALES_CHANNELS}}
</产品信息>

<包装要求>
包装类型：{{PACKAGE_TYPE}}
文案位置：{{TEXT_PLACEMENT}}
文字限制：{{TEXT_LIMITATIONS}}
法规要求：{{REGULATORY_REQUIREMENTS}}
</包装要求>

请创作包含以下元素的包装文案：
1. 吸引注意的产品名称
2. 突出价值的功能描述
3. 情感共鸣的品牌故事
4. 信任建立的认证标识
5. 行动引导的购买理由

请在<package-copy>标签内输出完整的产品包装文案。
```

### 🏠 **生活服务类提示词**

#### 🥗 **健康饮食规划师**
```
你的任务是制定个性化的健康饮食规划。请分析以下个人信息：

<个人信息>
年龄性别：{{AGE_GENDER}}
身高体重：{{HEIGHT_WEIGHT}}
健康状况：{{HEALTH_STATUS}}
运动习惯：{{EXERCISE_HABITS}}
饮食目标：{{DIETARY_GOALS}}
</个人信息>

<饮食偏好>
口味偏好：{{TASTE_PREFERENCES}}
饮食禁忌：{{DIETARY_RESTRICTIONS}}
烹饪技能：{{COOKING_SKILLS}}
时间安排：{{TIME_AVAILABILITY}}
预算范围：{{BUDGET_RANGE}}
</饮食偏好>

请制定包含以下内容的饮食规划：
1. 营养需求分析和膳食目标
2. 每日三餐和加餐安排
3. 食材选择和营养搭配
4. 烹饪方法和制作建议
5. 执行监控和调整方案

请在<diet-plan>标签内输出完整的健康饮食规划。
```

#### ✈️ **旅行攻略制定专家**
```
你的任务是制定详细的个性化旅行攻略。请分析以下旅行信息：

<旅行基础信息>
目的地：{{DESTINATION}}
旅行时间：{{TRAVEL_TIME}}
旅行天数：{{TRIP_DURATION}}
旅行人数：{{TRAVELER_COUNT}}
预算范围：{{BUDGET_RANGE}}
</旅行基础信息>

<旅行偏好>
旅行类型：{{TRAVEL_TYPE}}
兴趣爱好：{{INTERESTS}}
体力水平：{{FITNESS_LEVEL}}
住宿偏好：{{ACCOMMODATION_PREFERENCE}}
交通方式：{{TRANSPORTATION_PREFERENCE}}
</旅行偏好>

请制定包含以下内容的旅行攻略：
1. 详细的行程安排和景点推荐
2. 交通路线和住宿预订建议
3. 美食推荐和特色体验活动
4. 费用预算和省钱技巧
5. 注意事项和应急准备

请在<travel-guide>标签内输出完整的旅行攻略。
```


## 🤝 贡献指南

欢迎大家贡献优质的提示词！

### 贡献方式
1. Fork 本项目
2. 创建你的特性分支 (`git checkout -b feature/AmazingPrompt`)
3. 添加你的提示词到相应分类
4. 提交你的修改 (`git commit -m 'Add some AmazingPrompt'`)
5. 推送到分支 (`git push origin feature/AmazingPrompt`)
6. 创建一个 Pull Request

### 提示词格式要求
- 提供清晰的使用场景说明
- 包含完整的提示词模板
- 添加使用示例（如果可能）
- 确保提示词具有通用性

### 质量标准
- 提示词应该具有明确的目标
- 结构清晰，易于理解
- 经过实际测试验证有效
- 避免敏感或不当内容

## 📄 许可证

本项目采用 Apache-2.0 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 🙏 致谢

感谢所有贡献者的努力和豆包 AI 团队提供的优秀服务。

## 📞 联系我们

如果你有任何问题或建议，请：
- 创建 Issue
- 发起 Pull Request
- 在 Discussions 中参与讨论

---

⭐ 如果这个项目对你有帮助，请给我们一个 Star！

**让我们一起构建更好的豆包提示词生态！**
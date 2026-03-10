# AutoClaw Skills

AutoClaw 内置 Skills 收录，可直接用于 OpenClaw / Claude Code / OpenCode 等 Agent。

每个技能目录通常包含：

- `SKILL.md`：技能说明、触发条件、工作流
- `README.md`（部分技能）：补充介绍与示例
- `scripts/`、`templates/`（可选）：脚本与模板资源

## 技能范围

### 开发工程

- [`code`](./code-1.0.4/SKILL.md)：提供从规划、实现到验证与测试的完整编码工作流。
- [`git-essentials`](./git-essentials-1.0.0/SKILL.md)：汇总常用 Git 命令与协作流程，覆盖版本管理和分支协作。
- [`test-runner`](./test-runner-1.0.0/SKILL.md)：提供跨语言测试框架选型与测试编写/执行实践。
- [`tmux`](./tmux-1.0.0/SKILL.md)：用于远程控制 tmux 会话，适合交互式 CLI 和多会话编排。

### 安全与审计

- [`security-auditor`](./security-auditor-1.0.0/SKILL.md)：面向 OWASP 场景进行安全审计并给出可执行修复建议。
- [`clawdefender`](./clawdefender-1/SKILL.md)：扫描技能和外部输入，拦截提示词注入、命令注入等风险。
- [`skill-vetter`](./skill-vetter-1.0.0/SKILL.md)：在安装第三方技能前做安全审查，识别高风险行为与可疑模式。

### 内容与增长

- [`blog-writer`](./blog-writer-0.1.0/SKILL.md)：按作者风格生成博客与长文内容，并支持从调研到发布流程。
- [`copywriting`](./copywriting-0.1.0/SKILL.md)：用于撰写转化导向文案，如落地页、邮件、广告与 CTA。
- [`content-strategy`](./content-strategy-0.1.0/SKILL.md)：构建内容营销策略，覆盖内容规划、分发、复用与指标跟踪。
- [`seo`](./seo-1.0.3/SKILL.md)：提供站点审计、关键词研究、内容优化与技术 SEO 的综合支持。

### 研究与分析

- [`market-research`](./market-research-1.0.0/SKILL.md)：用于市场规模测算、竞品分析与机会验证。
- [`backtest-expert`](./backtest-expert-0.1.0/SKILL.md)：指导量化策略回测与稳健性评估，降低过拟合与偏差风险。
- [`research-paper-writer`](./research-paper-writer-0.1.0/SKILL.md)：按 IEEE/ACM 学术规范组织并撰写研究论文。

### 办公协作（飞书）

- [`feishu-doc`](./feishu-doc-1.2.7/SKILL.md)：读取和写入飞书文档/表格/多维表格，并可转换为 Markdown。
- [`feishu-send-file`](./feishu-send-file/SKILL.md)：通过 Feishu API 向群组或用户发送文件附件。
- [`feishu-chat-history`](./feishu-chat-history/SKILL.md)：拉取飞书群聊历史消息并输出结构化总结。

### AutoGLM 工具链

- [`autoglm-websearch`](./autoglm-websearch/SKILL.md)：调用 AutoGLM Web Search 做联网检索与实时信息查询。
- [`autoglm-open-link`](./autoglm-open-link/SKILL.md)：打开指定网页并提取正文，便于摘要与深度分析。
- [`autoglm-generate-image`](./autoglm-generate-image/SKILL.md)：根据文本描述调用 AutoGLM 文生图能力生成图片。

## 贡献说明

欢迎提交新技能或优化现有技能：

1. 新建独立技能目录
2. 提供清晰的 `SKILL.md`
3. 补充必要脚本/模板与使用示例
4. 提交 PR，说明技能目标、触发条件和边界

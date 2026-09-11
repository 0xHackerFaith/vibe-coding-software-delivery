# Vibe Coding 软件交付清单

这是一套给软件团队和项目负责人的 Vibe Coding 交付资料，重点不在于生成了多少代码，而在于项目能不能被验证、上线、维护和继续迭代。

## 这套资料解决什么问题

AI 编程工具可以快速生成页面、接口、测试草稿和文档初稿，但能运行的演示不等于完成软件交付。项目仍然需要有人确认业务目标、权限边界、数据风险、测试范围、部署方式和后续责任。

本仓库适合：

- 使用 Cursor、Claude Code、GitHub Copilot 等工具做原型或生产系统；
- 需要把 AI 生成代码纳入团队审查和 CI 流程；
- 准备上线 SaaS、Web 系统、AI Agent 或企业内部工具；
- 想在项目验收时同时检查工程资产和业务结果。

## 目录

| 路径 | 用途 |
|---|---|
| [`docs/01-vibe-coding-delivery-checklist.md`](docs/01-vibe-coding-delivery-checklist.md) | 从业务理解到上线后的完整交付清单 |
| [`docs/02-ai-code-review-checklist.md`](docs/02-ai-code-review-checklist.md) | AI 生成代码的审查、测试和合并检查 |
| [`templates/project-acceptance.md`](templates/project-acceptance.md) | 项目验收记录模板 |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | 如何补充和修订清单 |

## 快速使用

1. 复制对应模板到项目文档目录。
2. 先写清业务目标、用户角色、范围和验收条件。
3. 每次 AI 生成或修改一小块可验证的能力。
4. 让代码审查、自动化测试和部署检查成为合并条件。
5. 上线后记录故障、使用情况和业务指标，再决定下一轮工作。

清单不是项目管理流程的替代品。涉及资金、隐私、权限、多人协作或关键业务的系统，应结合组织的安全、合规和发布制度使用。

## 延伸阅读

关于 Vibe Coding 项目中业务判断、代码质量、上线运维和持续维护如何衔接，可以阅读官网文章：[Vibe Coding 软件开发：AI 写代码后，团队交付什么](https://codex-inc.cn/insights/vibe-coding-software-delivery-business-value/)。

## 贡献原则

- 清单要能在真实项目中执行，不写空泛口号。
- 每个检查项尽量对应一个证据、一次测试或一个明确责任人。
- 不把 AI 工具输出当作事实，不在没有来源时添加效果、排名或客户结果。
- 发现问题时优先补充判断条件和示例，而不是简单增加条目数量。

## License

本仓库暂不声明开源许可证。确定仓库归属和授权方式后，再补充正式 License 文件。

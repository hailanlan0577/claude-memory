# Claude记忆管理系统

本仓库用于存储和管理与Claude AI助手的对话记忆，提供结构化的知识库和上下文连续性。

## 核心文件

- [AI记忆管理规范](./ai-memory-protocol.md) - 定义了记忆管理的标准流程和格式
- [记忆恢复索引](./memory-index.md) - 专为AI记忆恢复设计的主索引
- [当前项目状态](./current-state.md) - 所有项目的最新状态概览
- [对话历史索引](./chat-index.md) - 所有历史对话的分类索引
- [提示词模板](./prompt-templates.md) - 标准化提示词模板

## 项目目录

- [GitHub AI对话记忆系统](./projects/memory-system/) - 基于GitHub的对话记忆管理系统
- [包包进销存系统](./projects/qiwei/) - 基于企业微信智能表格的包包进销存系统

## 如何使用

### 恢复记忆

在与Claude开始新对话时，使用以下提示词：

```
请阅读我GitHub仓库 https://github.com/hailanlan0577/claude-memory 中的ai-memory-protocol.md、memory-index.md和current-state.md文件，恢复我们的对话记忆。
```

### 保存对话

在对话结束时，使用以下提示词：

```
请根据 https://github.com/hailanlan0577/claude-memory 中的ai-memory-protocol.md规范，将本次关于[主题]的对话存入GitHub记忆系统，并更新相关索引文件。
```

更多详细信息，请参阅[提示词模板](./prompt-templates.md)。
# GitHub AI对话记忆系统提示词模板

## 读取提示词（用于新对话开始时）

```
请从我的GitHub仓库 https://github.com/hailanlan0577/claude-memory 恢复我们之前的对话记忆。首先，请查看并理解根目录中的"ai-memory-protocol.md"文件，这是我们的记忆管理规范。按照该规范，优先阅读memory-index.md和current-state.md文件，然后关注与[当前主题]相关的最近对话记录。完成记忆恢复后，请简要确认你已理解的上下文。
```

### 简短版

```
请阅读我GitHub仓库 https://github.com/hailanlan0577/claude-memory 中的ai-memory-protocol.md、memory-index.md和current-state.md文件，恢复我们的对话记忆。
```

## 写入提示词（用于对话结束时）

```
请将我们的对话保存到GitHub记忆系统。请首先查看 https://github.com/hailanlan0577/claude-memory 根目录中的"ai-memory-protocol.md"文件了解记忆管理规范，然后按照该规范创建标准格式的对话记录文件。这次对话关于[主题]，属于[项目名称]，使用标签#标签1 #标签2。请同时更新chat-index.md、memory-index.md和current-state.md文件。
```

### 简短版

```
请根据 https://github.com/hailanlan0577/claude-memory 中的ai-memory-protocol.md规范，将本次关于[主题]的对话存入GitHub记忆系统，并更新相关索引文件。
```

## 查询特定记忆提示词

```
请按照 https://github.com/hailanlan0577/claude-memory 中的ai-memory-protocol.md规范，在GitHub记忆系统中查找关于[特定主题]的历史对话，特别关注[时间范围]内的讨论和包含#[特定标签]的内容。
```
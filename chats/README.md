# 对话记录目录

本目录存储所有与Claude的对话记录，按年月组织。

## 目录结构

```
chats/
├── 2025-03/             # 2025年3月的对话
│   ├── 2025-03-06_记忆系统_设计与实施.md
│   └── ...
├── 2025-04/             # 2025年4月的对话 
│   └── ...
└── ...
```

## 文件命名规范

所有对话文件使用以下命名格式：
```
YYYY-MM-DD_项目标识_主题关键词.md
```

例如：
- `2025-03-06_记忆系统_设计与实施.md`
- `2025-03-10_数据分析_销售预测模型.md`

## 对话内容格式

每个对话文件应包含以下结构：

```markdown
# 对话：[主题]

- **日期**：YYYY-MM-DD
- **参与者**：AI助手、用户
- **主题**：[简短描述]
- **标签**：#标签1, #标签2, #标签3
- **相关文件**：[相关文件的链接]

## 摘要

[对话的简短摘要，不超过5个要点]

## 对话内容

**用户**：[用户输入]

**AI助手**：[AI回复]

[...完整对话内容...]

## 重要结论

- [结论1]
- [结论2]
- ...

## 后续行动

- [ ] [行动1]
- [ ] [行动2]
- ...
```

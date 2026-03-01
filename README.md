# Content Hub 📚

> 小红书内容创作中心 - PKM / AI / Vibe Coding

---

## 📂 目录结构

```
content-hub/
├── config/           # 配置文件
│   └── persona.md    # 人设配置
├── templates/        # 模板文件
│   └── xiaohongshu-note.md  # 小红书笔记模板
├── prompts/          # 写作 Prompts
│   ├── 01-选题猎手.md
│   ├── 02-封面设计师.md
│   ├── 03-爆款标题大师.md
│   ├── 04-图文内容师.md
│   ├── 05-话题标签师.md
│   └── 06-发布优化师.md
├── drafts/           # 草稿区（待发布）
│   ├── pkm/          # PKM/第二大脑
│   ├── ai/           # AI 领域
│   └── vibe-coding/  # Vibe Coding
├── published/        # 已发布（归档）
│   ├── pkm/
│   ├── ai/
│   └── vibe-coding/
└── assets/           # 素材
    └── images/       # 图片
```

---

## 🚀 快速开始

### 1. 创建新笔记

1. 在 `drafts/` 对应领域目录下创建新笔记
2. 使用 `templates/xiaohongshu-note.md` 模板
3. 按 prompts 顺序逐步填充内容

### 2. 写作流程

```
01-选题猎手 → 确定选题
02-封面设计师 → 设计封面
03-爆款标题大师 → 生成标题
04-图文内容师 → 撰写正文
05-话题标签师 → 选择标签
06-发布优化师 → 发布策略
```

### 3. 发布后

- 移动笔记到 `published/` 目录
- 填写数据追踪
- 添加复盘笔记

---

## 📊 内容领域

| 领域 | 占比 | 核心主题 |
|------|------|----------|
| PKM/第二大脑 | 33% | Obsidian、Notion、知识图谱、笔记方法 |
| AI 领域 | 33% | AI 工具、提示词、应用实践 |
| Vibe Coding | 33% | Claude Code、OpenCode、编程新范式 |

---

## 🎭 人设定位

**双重身份**：实践者 + 工具猎人

- 亲切、接地气、像朋友聊天
- 真实不装、有干货、有温度
- 分享真实体验、帮用户筛选好工具

详见 `config/persona.md`

---

## 📝 状态标记

| 状态 | 说明 |
|------|------|
| `draft` | 草稿，待完善 |
| `ready` | 完成待发布 |
| `published` | 已发布 |
| `archived` | 已归档 |

---

## 🔄 与 MacBook Air 同步

```bash
# 主力 Mac 推送
git add . && git commit -m "Add new content" && git push

# MacBook Air 拉取
git pull
```

---

## 📅 更新日志

- **2026-03-01** - 初始化项目，创建基础结构

# domn-film-seedance-format

![domn-film-seedance-format 封面](assets/readme/hero.webp)

> Seedance 生视频提示词格式规范。

## 是什么

Seedance 生视频提示词格式规范。本仓库是一个 Agent 技能（SKILL.md 为唯一权威定义），把上面的方法论沉淀为可被对话触发的可执行流程。

## 怎么做（工作流）

<p align="center">
  <img src="./assets/readme/workflow.svg" width="100%" alt="domn-film-seedance-format 工作流：锁骨架 → 写对白 → 排镜头 → 定参数。对白与语言写法最易写糊，单列经验">
</p>

1. **锁骨架**
2. **写对白**
3. **排镜头**
4. **定参数**

## 怎么用

将本仓库放入支持 `SKILL.md` 的 Agent 技能目录：

- **WorkBuddy**：`~/.workbuddy/skills/domn-film-seedance-format/`
- **Codex / 其他**：对应 skills 目录

然后在对话中触发，例如：

```
用 domn-film-seedance-format 帮我处理一段需求。
```

## 依赖

纯提示词格式规范，供 Seedance / 即梦等文生视频模型使用.

## 仓库结构

```
domn-film-seedance-format/
├── SKILL.md                 # 技能定义（唯一权威）
├── references/              # 方法论弹药库
├── assets/                  # 模板 / 占位素材
└── assets/readme/           # 本 README 的视觉资产（hero.webp / workflow.svg）
```

## 许可

本仓库内容以 `SKILL.md` 为唯一权威定义。如附带 `LICENSE` 文件，以其为准。

---

*README 由 `beautify-github-readme` 生成 · 封面图来自作者作品集，强调色由封面图采样派生。*

# tech-prompt

技术领域全能 AI 助手 Skill - 面试准备 + 生产实战 + 体系化学习

## 简介

tech-prompt 赋能 OpenCode AI 同时服务三种角色：

- **技术学习者**：原理讲解、概念辨析、循序渐进
- **面试求职者**：高频考点、答题技巧、表达话术
- **生产开发者**：故障排查、性能优化、工程实践

GitHub: https://github.com/Aiden-zht/tech-prompt

本地目录: `~/aiden_zht/tech-prompt/`

---

## 快速开始

### 加载 Skill

在 opencode 会话中执行：

```
/skill tech-prompt
```

或指定路径：

```
/skill ~/aiden_zht/tech-prompt/SKILL.md
```

或远程加载：

```
/skill https://raw.githubusercontent.com/Aiden-zht/tech-prompt/main/SKILL.md
```

---

## 自动识别场景

根据问题关键词自动判断用户需求：

| 关键词 | 场景 | 回答重点 |
|--------|------|----------|
| "是什么" / "原理" / "解释" | 学习 | 概念 + 原理 + 图解 |
| "面试" / "八股文" / "考什么" | 面试 | 考点 + 话术 + 技巧 |
| "生产" / "故障" / "排查" / "优化" | 生产 | 方案 + 命令 + 案例 |
| "区别" / "对比" / "选型" | 选型 | 优缺点 + 适用场景 |

---

## 更新 Skill

```bash
cd ~/aiden_zht/tech-prompt

# 编辑 SKILL.md
vim SKILL.md

# 推送更新
git add .
git commit -m "feat: 更新描述"
git push origin master
```

---

## 适用技术领域

- 编程语言: Go、Python、Java、C++、Rust、JavaScript/TypeScript
- 系统基础: 操作系统、计算机网络、数据结构与算法
- 后端开发: 分布式系统、微服务、数据库、消息队列、缓存
- 基础设施: Linux、容器(Docker/Kubernetes)、云原生、监控
- 数据与AI: 机器学习、深度学习、大数据、GPU 异构计算
- 架构设计: 系统架构、性能优化、高可用设计
- DevOps: CI/CD、GitOps、运维自动化、安全

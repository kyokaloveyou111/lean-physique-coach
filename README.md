# 薄肌训练助手 · Lean Physique Coach

一个中文个人训练 Skill：今天知道怎么练，练完能记录，每周知道该不该调整。

灵感来自用户提供的 Alan 训练视频转写稿，保留规律训练、渐进进步、足量蛋白质、能量调整与坚持，并修订强制加重、极低体脂和过度节食等说法。**独立整理的非官方项目，与 Alan 无隶属或授权关系。**

## 直接阅读：无需安装

**本仓库公开，以下完整内容无需登录、无需安装 Skill 即可阅读。** 安装是为了让 AI 按这些规则帮助你安排和记录训练；只想了解方法，直接点击：

- [完整 Skill 指令：评估、今日训练、记录与复盘](skills/lean-physique-coach/SKILL.md)
- [完整训练方法：具体动作、组次、休息和替代方案](skills/lean-physique-coach/references/training.md)
- [完整饮食方法：蛋白质、外食和热量调整](skills/lean-physique-coach/references/nutrition.md)
- [训练历程：酸痛、漏练、平台期和长期维持](skills/lean-physique-coach/references/journey.md)
- [Alan 原观点与本项目调整的逐项对照](skills/lean-physique-coach/references/alan-method.md)

## 方法先看这里

每天以 30–40 分钟为基础，热身、休息和记录都计入时间；忙时用 15–20 分钟简化版。以下为可按个人条件调整的成人一般模板，具体动作见上方完整训练方法。

| 日期 | 安排 |
|---|---|
| 周一 | 全身力量 A，偏胸肩 |
| 周二 | 轻松游泳；无泳池可步行或单车 |
| 周三 | 全身力量 B，偏背部 |
| 周四 | 步行与轻活动，也可休息 |
| 周五 | 全身力量 C，兼顾腿臀、肩和核心 |
| 周六 | 恢复良好时第四次力量选做，或用熟悉且耐受的球类替换 |
| 周日 | 轻活动或休息，复盘本周 |

执行抓住五件事：

1. **保守起步**：恢复训练前两周通常每动作两组，主动作 8–12 次、辅助 10–15 次，保留约 3–4 次余力。重量根据动作和当前能力选择。
2. **逐步进步**：先把动作做好、增加次数；达到次数上限、动作稳定且恢复正常后，再增加最小重量。允许维持和减量，不要求每次加重。
3. **吃够再调整**：健康成人规律力量训练，默认参考每日蛋白质 1.6–2.0 g/kg；保留正常主食和多样食物。先记录饮食与趋势，再决定热量调整。
4. **记录事实**：练完记各组重量、次数、余力、时长和身体反馈。体重看至少两周趋势，腰围每周同条件测量，单日变重不触发减餐。
5. **长期坚持**：漏练后按 A/B/C 顺序继续，忙时缩短，疲劳时减量或休息。第四次力量与球类互相替换，不额外叠加；疼痛加重、肿胀或不稳时停止相关动作并评估。

这份公开模板没有任何人的真实身体档案。每位使用者都应建立自己的基线，按条件和反馈调整；详细证据及适用范围见 [来源](skills/lean-physique-coach/references/sources.md)。

## 能做什么

- 首次评估条件，建立体重、腰围和训练表现基线。
- 每周三次核心力量、第四次选做，其他天提供游泳、步行或合适的球类选项。
- 每天默认 30–40 分钟；忙时 15–20 分钟；疲劳时减量或休息。
- 根据真实记录决定增加次数、加重、维持或减量。
- 处理外食、漏练、体重波动、平台期与长期维持。

目标是肌肉线条与长期习惯，不承诺特定体脂、外形时间或社交结果；不能诊断伤病或代替术后康复／医疗饮食指导。

## 安装与调用

技能目录：[skills/lean-physique-coach](skills/lean-physique-coach/SKILL.md)。无需 API key、GitHub 连接或补剂；安装后训练对话可读取本地参考文件。宿主模型本身的联网要求由所用产品决定。

在支持 Skill Installer 的 Codex 中发送：

```text
使用 $skill-installer，从 https://github.com/kyokaloveyou111/lean-physique-coach
安装 skills/lean-physique-coach 目录里的 Skill。
```

也可下载仓库，将完整 `skills/lean-physique-coach` 文件夹复制到 `~/.agents/skills/`，或项目的 `.agents/skills/`。不要只复制 SKILL.md。若未发现新技能，重启 Codex。参考 [官方文档](https://learn.chatgpt.com/docs/build-skills)。这是独立 Skill，未进入插件商店。

```text
使用 $lean-physique-coach，先了解我的情况，安排容易坚持的一周。
使用 $lean-physique-coach，我今天只有 20 分钟，昨天练过背，怎么练？
使用 $lean-physique-coach，记录今天的训练：……
使用 $lean-physique-coach，结合这两周日志复盘，别因为一天变重就让我减餐。
```

桌面中也可从技能列表选择，入口以宿主实际功能为准。

## 方法与模板

| 内容 | 入口 |
|---|---|
| 排程、动作、进步与替代 | [训练安排](skills/lean-physique-coach/references/training.md) |
| 蛋白质、外食和热量调整 | [饮食](skills/lean-physique-coach/references/nutrition.md) |
| 这条路会遇到什么 | [训练历程](skills/lean-physique-coach/references/journey.md) |
| 原观点与改编差异 | [方法对照](skills/lean-physique-coach/references/alan-method.md) |
| 证据与适用范围 | [来源](skills/lean-physique-coach/references/sources.md) |
| 首次评估 | [资料模板](skills/lean-physique-coach/assets/profile-template.md) |
| 每次训练 | [日志模板](skills/lean-physique-coach/assets/session-template.md) |
| 每周调整 | [复盘模板](skills/lean-physique-coach/assets/weekly-template.md) |
| 如何对话 | [虚构示例](examples/conversations.md) |

## 隐私、验证与许可

公开仓库没有创建者的身体数据、手术史、照片或真实日志。填写后的资料应保存在仓库外；`.gitignore` 只是第二层防护。公开 Issues 只用虚构数据讨论技能问题。

[场景验收](tests/scenarios.md)是人工演练，不是独立模型评测、临床测试或真实训练效果。格式通过不能证明教练效果。

原创技能、模板与说明采用 [MIT 许可](LICENSE)。链接到的 Alan 内容和文献不在本项目许可范围内；本仓库未复制整篇转写稿、他人图片或书籍。

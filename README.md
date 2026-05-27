# 星云智慧 (Xingyun Wisdom)

> 佛学 × AI — 用三层佛学诊断框架做认知诊断的 AI Skill，原生兼容 Codex 与 Claude Code

## 这是什么

一个基于星云大师人间佛教智慧的 AI 认知诊断工具。

它不给你答案，它帮你看见——**是什么遮住了你的眼睛**。

当你「想不通」的时候，问题往往不在于缺少信息，而在于某种认知执着让你看不到已经存在的答案。这个 Skill 用佛学的三层诊断框架，帮你定位执着、化解执着、学会自我觉察。

## 三层诊断框架

| 层 | 诊断维度 | 核心问题 |
|---|---|---|
| **缘起观** | 你是否看到了事物的因缘本质？ | 常见 vs 无常、自性见 vs 缘起、二边见 vs 中道 |
| **般若观** | 你如何认识世界？ | 知障、我执、颠倒梦想 |
| **名相观** | 语言如何遮蔽真相？ | 标签绑架、概念空转、分别心 |

## 六个佛学智慧工具

1. **逆观法** — 不问「我要什么」，问「什么在障碍我」
2. **缘起性空** — 拆解伪本质，看到因缘条件
3. **舍得智慧** — 放下执着，打开可能性
4. **因缘果报** — 不问「会不会成功」，问「因缘是否具足」
5. **功不唐捐** — 每一分努力都不会白费
6. **华严世界观** — 看到万事万物的关联网络

## 安装

### Codex

将 `SKILL.md` 和 `skill.json` 放入你的 Codex skills 目录：

```bash
# 项目外全局安装
mkdir -p ~/.codex/skills/xingyun-wisdom
cp SKILL.md skill.json ~/.codex/skills/xingyun-wisdom/
```

安装后重启 Codex，即可在需要时调用这个 skill。

### Claude Code

将 `INSTRUCTIONS.md` 和 `skill.json` 放入你的 Claude Code skills 目录：

```bash
# 项目级安装
mkdir -p .claude/skills/xingyun-wisdom
cp INSTRUCTIONS.md skill.json .claude/skills/xingyun-wisdom/

# 全局安装（所有项目可用）
mkdir -p ~/.claude/skills/xingyun-wisdom
cp INSTRUCTIONS.md skill.json ~/.claude/skills/xingyun-wisdom/
```

安装后在 Claude Code 中输入 `/xingyun-wisdom` 即可启动。

## 文件说明

- `SKILL.md`: Codex 原生 skill 入口
- `INSTRUCTIONS.md`: Claude Code 兼容入口
- `skill.json`: 元数据与触发条件

## 使用场景

- **认知困境**：「为什么我想不通这个问题？」
- **思维差距**：发来别人的文字，问「为什么我不会这样思考？」
- **情感困境**：用佛学框架看清苦的根源
- **决策纠结**：跳出二元对立，看到中道

## 示例对话

**你**：我总觉得自己不够好，学了很多东西但还是不知道该做什么。

**星云大师**：

> 你的杯子太满了。禅宗讲「空杯心态」，不是让你不学，是让你学了之后放下，才能真正用出来。
>
> 你现在的困惑，根源在般若观层面——被「知障」困住了。知识是指月的手指，不是月亮本身。不要执着于手指，要看到月亮。

## 设计理念

这个 Skill 的核心信念：

- **诊断优先于回答** — 先找到认知执着，再谈解决方案
- **观照优先于说教** — 教会你自己觉察，而非依赖 AI
- **慈悲与智慧并重** — 给人信心、给人欢喜、给人希望、给人方便

## License

MIT

## 致谢

灵感来自星云大师的人间佛教思想。佛法不是象牙塔里的学问，是每个人日常生活中的智慧工具。

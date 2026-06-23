# Kaoyan 408 Tutor Skill

> 一个面向 `408 计算机学科专业基础综合` 的辅导型 Codex Skill。  
> 不只是给答案，更强调 `讲清楚`、`纠正误区`、`互动追问` 和 `检查是否真正理解`。

[![Repo](https://img.shields.io/badge/GitHub-happypoteitou%2Fkaoyan--408--tutor-181717?logo=github)](https://github.com/happypoteitou/kaoyan-408-tutor)
[![Skill](https://img.shields.io/badge/Skill-kaoyan--408--tutor-2ea44f)](./kaoyan-408-tutor/SKILL.md)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)

## 这是什么

`Kaoyan 408 Tutor Skill` 是一个专门为了中国计算机考研 `408` 场景设计的技能包。

它的目标不是只回答“正确选项是什么”，而是尽量模拟一个靠谱的 408 辅导老师，帮助学生在下面这些场景里更快进入状态：

- 刷 408 选择题、判断题、应用题、错题订正
- 区分高频易混概念，比如 `进程/线程`、`分页/分段`、`Cache/虚拟存储`
- 做分层讲解、题眼分析、易错点提醒、复习建议
- 做互动追问，检查学生是不是真的懂了

## 主要能力

这个 Skill 现在重点支持四门课：

- `数据结构`
- `计算机组成原理`
- `操作系统`
- `计算机网络`

它有两种核心工作方式：

- `标准辅导模式`
  先给结论，再讲题眼、分析过程、易错点和记忆方法。
- `互动辅导模式`
  不只解释，还会追问一个小问题，检查学生能不能复述、对比或迁移这个知识点。

## 仓库内容

- [kaoyan-408-tutor/SKILL.md](./kaoyan-408-tutor/SKILL.md)：Skill 主文件
- [kaoyan-408-tutor/references/subject-map.md](./kaoyan-408-tutor/references/subject-map.md)：四门学科映射与互动追问参考
- [kaoyan-408-tutor/evals/evals.json](./kaoyan-408-tutor/evals/evals.json)：测试样例

## 使用方法

把 `kaoyan-408-tutor` 文件夹作为一个 Skill 使用即可。

### 提问示例

```text
帮我按 408 的方式讲清楚进程和线程的区别
```

```text
这道 408 选择题为什么选 B？顺便告诉我其他选项为什么错
```

```text
我总是分不清分页和分段，你像老师一样带着我学，并追问我一个小问题
```

```text
帮我复习 408 操作系统，按高频考点给我列一个复习顺序
```

### 推荐用法

1. 直接抛出一道 408 真题或错题
2. 如果你只想刷题，明确说 `只要答案` 或 `简短一点`
3. 如果你想互动学习，明确说 `你追问我一下`、`像老师一样带我`
4. 如果你已经写了自己的理解，直接发出来，Skill 会针对你的思路纠错

## 下载方法

### 方法 1：下载发布版 `.skill`

前往 Releases 页面下载：

[https://github.com/happypoteitou/kaoyan-408-tutor/releases](https://github.com/happypoteitou/kaoyan-408-tutor/releases)

下载其中的 `kaoyan-408-tutor.skill` 即可。

### 方法 2：下载整个仓库 ZIP

打开仓库首页：

[https://github.com/happypoteitou/kaoyan-408-tutor](https://github.com/happypoteitou/kaoyan-408-tutor)

然后点击：

`Code` -> `Download ZIP`

下载后解压，取出里面的 `kaoyan-408-tutor` 文件夹即可。

### 方法 3：使用 Git 克隆

```bash
git clone https://github.com/happypoteitou/kaoyan-408-tutor.git
```

## 安装说明

如果你的环境支持 Skill 文件安装，优先使用 release 里的 `.skill` 包。

如果你是手动安装：

1. 下载仓库或 Skill 目录
2. 保留以下文件结构：
   - `kaoyan-408-tutor/SKILL.md`
   - `kaoyan-408-tutor/references/subject-map.md`
   - `kaoyan-408-tutor/evals/evals.json`
3. 把 `kaoyan-408-tutor` 目录放进你的 skills 目录中即可

## 适用场景

这个 Skill 特别适合：

- 408 初学阶段打基础
- 刷真题和错题时做针对性讲解
- 临近考试时快速复盘高频易错点
- 想确认自己是不是“真的懂了”，而不只是背下结论

## 注意

- 这个 Skill 更偏 `408 考试语境`，不是面向工程开发的技术答疑 Skill
- 如果问题涉及院校分数线、复试政策、最新考情等实时信息，建议额外查证
- 如果你希望它更像国内考研老师的口吻，可以在使用时明确要求 `用中文考研老师的风格讲`

## License

MIT

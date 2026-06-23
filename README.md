# Kaoyan 408 Tutor Skill

一个面向 `408 计算机学科专业基础综合` 备考场景的 Codex Skill。

它的目标不是只给答案，而是像老师一样辅导学生理解 `数据结构`、`计算机组成原理`、`操作系统`、`计算机网络` 这四门核心内容，尤其适合拿来处理：

- 408 选择题、判断题、应用题、错题订正
- 易混概念对比，比如 `进程/线程`、`分页/分段`、`Cache/虚拟存储`
- 分层讲解、考点总结、互动追问、理解检查

## 简介

这个 Skill 会让模型更像一个 `408 考研辅导老师`，而不是一个通用问答助手。

它支持两种主要风格：

- `标准辅导模式`：先给结论，再讲题眼、分析过程、易错点和记忆方法
- `互动辅导模式`：除了讲解，还会主动追问一个小问题，检查学生是否真的理解了

仓库内容如下：

- [kaoyan-408-tutor/SKILL.md](./kaoyan-408-tutor/SKILL.md)：Skill 主文件
- [kaoyan-408-tutor/references/subject-map.md](./kaoyan-408-tutor/references/subject-map.md)：四门学科映射与互动追问参考
- [kaoyan-408-tutor/evals/evals.json](./kaoyan-408-tutor/evals/evals.json)：测试样例

## 使用方法

把 `kaoyan-408-tutor` 文件夹作为一个 Skill 使用即可。

适合的提问方式示例：

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

推荐使用方式：

1. 直接抛出一道 408 真题或错题
2. 如果你只想刷题，明确说 `只要答案` 或 `简短一点`
3. 如果你想互动学习，明确说 `你追问我一下`、`像老师一样带我`
4. 如果你已经写了自己的理解，直接发出来，Skill 会针对你的思路纠错

## 下载方法

### 方法 1：直接下载整个仓库

打开仓库首页：

[https://github.com/happypoteitou/kaoyan-408-tutor](https://github.com/happypoteitou/kaoyan-408-tutor)

然后点击：

`Code` -> `Download ZIP`

下载后解压，取出里面的 `kaoyan-408-tutor` 文件夹即可。

### 方法 2：只下载 Skill 目录

如果你只关心 Skill 本体，拿到这个目录即可：

`kaoyan-408-tutor/`

其中至少需要保留：

- `SKILL.md`
- `references/subject-map.md`
- `evals/evals.json`

### 方法 3：使用 Git 克隆

```bash
git clone https://github.com/happypoteitou/kaoyan-408-tutor.git
```

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


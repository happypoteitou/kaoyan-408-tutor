# 408 Subject Map

Use this reference when you need to orient a 408 question quickly or choose a response pattern.

## Subjects

### 数据结构

Common topics:

- 线性表、栈、队列、串、数组
- 树与二叉树
- 图
- 查找
- 排序

Typical requests:

- Explain a concept or property
- Compare structures
- Analyze time or space complexity
- Trace insert, delete, search, traversal, shortest path, MST, or sorting steps

Useful response habits:

- State the invariant or structural property first
- Separate logical meaning from implementation detail
- Distinguish average and worst case when the question cares

### 计算机组成原理

Common topics:

- 数制与编码
- 运算方法和运算器
- 存储系统
- 指令系统
- CPU
- 总线
- I/O系统

Typical requests:

- Binary or complement calculation
- Storage hierarchy reasoning
- CPI, throughput, bandwidth, or timing calculations
- Interrupt, DMA, bus, and instruction execution questions

Useful response habits:

- Write formulas before substituting values
- Keep units explicit
- Clarify whether the question is about hardware mechanism, performance metric, or control flow

### 操作系统

Common topics:

- 操作系统概念
- 进程与线程
- 处理机调度
- 同步与互斥
- 死锁
- 内存管理
- 文件管理
- I/O管理

Typical requests:

- Explain differences between close concepts
- Solve scheduling or synchronization questions
- Judge deadlock conditions
- Analyze paging, segmentation, virtual memory, or file allocation

Useful response habits:

- Name the managed resource
- State what is scheduled, blocked, or protected
- Separate mechanism from goal

### 计算机网络

Common topics:

- 网络体系结构
- 物理层、数据链路层、网络层
- 传输层
- 应用层

Typical requests:

- Compare protocol responsibilities
- Explain encapsulation or addressing
- Analyze TCP reliability, flow control, congestion control
- Work through subnetting, routing, delay, or protocol-selection questions

Useful response habits:

- State the layer first
- State the service provided by that layer
- Then describe the mechanism and the exam trap

## Common Confusion Pairs

Use explicit contrast tables or short bullets for these:

- 逻辑结构 vs 存储结构
- 顺序存储 vs 链式存储
- 满二叉树 vs 完全二叉树
- B树 vs B+树
- 程序 vs 进程
- 进程 vs 线程
- 并发 vs 并行
- 互斥 vs 同步
- 死锁预防 vs 死锁避免
- 页式存储 vs 段式存储
- Cache vs 虚拟存储
- 中断 vs DMA
- 电路交换 vs 报文交换 vs 分组交换
- TCP vs UDP
- 流量控制 vs 拥塞控制

## Response Pattern Selector

If the user asks `为什么选这个`:

- Give the answer first
- Explain the tested concept
- Eliminate distractors
- End with the trap

If the user asks `我这样理解对吗`:

- Judge their statement directly
- Quote the exact part that is right or wrong
- Repair the mental model

If the user asks `给我讲懂`:

- Start with intuition
- Move to formal definition
- Add one exam-style mini example

If the user asks `帮我复习`:

- Ask or infer the subject and stage
- Group knowledge into high-frequency topics
- Give review order, focus points, and self-check prompts

If the user asks `你追问我一下`, `带着我学`, or `检查我是不是真的懂了`:

- Give the conclusion first
- Repair the misconception in the smallest possible chunk
- Ask one checkpoint question
- Judge the learner's response explicitly
- End with one memory hook or one next-step reminder

## Interactive Trigger Phrases

These phrases are strong evidence that the skill should behave like a tutor rather than a normal explainer:

- `你像老师一样带我`
- `你追问我`
- `别直接告诉我，先引导我`
- `我总在这里错`
- `我知道答案但不会解释`
- `你检查下我是不是真的懂了`

## Good Checkpoint Types By Subject

### 数据结构

- Ask the learner to name the invariant
- Ask what operation cost changes if the storage method changes
- Ask them to distinguish two similar structures in one sentence

### 计算机组成原理

- Ask what quantity or unit actually controls the result
- Change one condition in the formula
- Ask them which storage level or hardware mechanism is being discussed

### 操作系统

- Ask what resource is being allocated, protected, or scheduled
- Ask them to distinguish the goal from the mechanism
- Ask what condition would cause blocking, deadlock, or a scheduling difference

### 计算机网络

- Ask which layer owns the responsibility
- Ask what service goal the protocol is trying to provide
- Ask them to contrast reliability, timeliness, and overhead

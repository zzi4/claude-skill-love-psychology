# 恋爱关系军师 · claude-skill-love-psychology

一个 [Claude](https://claude.com/claude-code) Agent Skill —— 让 Claude 化身一个**又清醒又靠谱的好哥们/好闺蜜**，陪你理清感情里的困惑，而不是只听一面之词就拍板、瞎给主意。

## 这个 skill 做什么

当你分享自己的爱情/亲密关系经历、感情困扰、与对象的相处或吵架、感情变淡、关系定位疑惑，或问"我该怎么和 ta 相处""我们到底咋了""ta 为啥这样""我是不是该分手"之类问题时，它会自动触发——哪怕你没明说"用心理学分析"。

它的定位是**军师/镜子，不是替你拿主意的外人**：

- 不急着下结论，先一步步带你把事情的全貌掏出来；
- 帮你把**事实**和**脑补**分开；
- 针对让你困惑或扎心的行为，把双方行为背后的**多种可能原因**都摊开（而不是死咬最伤人的那个解释）；
- 帮你看清这段关系里俩人到底**图对方啥**、各自给了对方啥；
- 最后把你推向和对象更真实的**深聊**——因为真能解决问题的话，永远得你俩自己说。

它**不会**输出"你就该分手/挽回/原谅"这种替你拍板的话，也**绝不**教操控/PUA/套路、不物化任何一方。遇到持续操控、孤立、人身威胁、暴力或精神虐待的苗头时，会优先提醒你寻求专业支持。

## 两种口吻模式

分析内核完全一样，只是说话的皮不同，可在开聊前或中途自由切换：

- **闺蜜模式（女性向）**——又护着你又敢戳醒你的好闺蜜，细腻、共情在前。
- **兄弟模式（男性向）**——跟你掏心窝、关键时刻敢拍你脑门的好哥们，干脆、直给。

## 背后的心理学框架

`references/frameworks.md` 收录了用来**扩充"行为原因可能性清单"**的专业底料（依恋理论、戈特曼冲突研究、爱的五种语言、EFT 负向循环、斯滕伯格爱情三角、社会交换/价值视角）。框架是用来打开可能性的，**不是用来贴标签下定论的**。

## 安装

把整个仓库放进 Claude Code 的 skills 目录即可：

```bash
git clone https://github.com/zzi4/claude-skill-love-psychology.git ~/.claude/skills/love-psychology
```

Windows (PowerShell)：

```powershell
git clone https://github.com/zzi4/claude-skill-love-psychology.git "$env:USERPROFILE\.claude\skills\love-psychology"
```

重启 Claude Code 后，相关话题会自动触发本 skill。

## 目录结构

```
.
├── SKILL.md                 # skill 主体（触发条件 + 工作流程 + 输出风格）
├── references/
│   └── frameworks.md        # 心理学框架详解（按需深入时加载）
└── README.md
```

## 许可

个人项目，自由取用。

# UGC 圈层洞察 Skill

帮助品牌与设计团队从当前 UGC 内容、评论和互动行为中，快速理解陌生圈层的概念、情绪、黑话、互动习惯与活动机会。

它不会停留在术语释义，而会从表层词汇继续下钻到核心实践、母文化、身份群体和关联概念。例如研究「痛屋」时，会同时追溯痛文化、二次元群体，以及痛包、痛车、痛娃等概念家族。

## 适用场景

- 快速进入陌生圈层或亚文化
- 为 UGC 活动寻找机制与参与动机
- 提炼圈内黑话、情绪张力和互动习惯
- 为视觉包装与品牌沟通提供依据

## 使用方式

在 Codex 中发送：

```text
请从 https://github.com/Sanshirou-34/ugc-circle-insight-skill/tree/main/skills/ugc-circle-insight 安装 ugc-circle-insight skill
```

安装后可以这样提问：

```text
使用 ugc-circle-insight 调研「痛屋」。
```

Skill 会先确认小红书、抖音等 UGC 平台的登录与授权状态，再开始研究；若平台无法访问，会明确标记证据缺口并降级使用公开网页信息。

## 研究节奏

默认先给出一版可快速阅读的圈层速览，再询问：

> 你是想做活动机制、视觉包装，还是品牌沟通？

用户选择方向后，再继续深挖。输出同时覆盖洞察和建议，但以活动玩法为主。

## 目录

```text
skills/ugc-circle-insight/
├── SKILL.md
├── agents/openai.yaml
└── references/
    ├── research-method.md
    └── report-template.md
```

## 数据边界

只使用当前可访问的公开内容或用户已授权访问的页面，不绕过登录、验证码、访问限制或平台安全机制。研究结论会按来源类型标记，并区分事实、观察、推断和建议，避免把单条内容误判为圈层共识。

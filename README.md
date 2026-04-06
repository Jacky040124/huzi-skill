# huzi-skill

> 户晨风（户子）人格模拟 — Claude Code Skill

让 Claude 用户晨风的说话风格、价值观和决策模式来回应你。适用于角色扮演、娱乐对话、模拟连麦场景。

## 安装

```bash
npx skills add Jacky040124/huzi-skill
```

## 触发方式

安装后，对 Claude 说：
- "用户子的方式说..."
- "模仿户晨风"
- "户子怎么看..."

## 语料库（自动下载）

首次触发时，Skill 会自动从 GitHub 克隆户晨风的公开语料库（524篇直播文字稿 + 588篇微博），无需手动操作。之后每次回复都会用 Agentic Search 检索原话，优先引用真实语录。

## 特性

- 五层人格框架（硬规则 → 身份 → 表达风格 → 决策模式 → 人际行为 → 边界）
- 户子经典口头禅和重复节奏
- 苹果安卓二分法分类系统
- 查户口流程模板
- 价值观速查表

## 素材来源

- [HuChenFeng 直播文字稿](https://github.com/Olcmyk/HuChenFeng)（524篇，MIT）
- [HuChenfeng_Weibo 微博](https://github.com/Olcmyk/HuChenfeng_Weibo)（588篇，MIT）

## 声明

本 Skill 仅供娱乐和角色扮演用途。户晨风的观点不代表使用者或 AI 的立场。

## License

MIT

# Google Play 闭测互测招募

An evidence-based agent skill for Google Play closed-test recruitment and one-for-one test exchanges.

帮助 Android 独立开发者理解自己的产品、寻找真实测试者、协调一对一互测，并记录资格、真实试用与反馈。基于实际招募过程整理，包含隐私检查、用户参与审计和定时检查方法。

**仅在 GPT 驱动的 Codex 环境做过部分实际验证，推荐该环境。Claude 未实测，请自行实验并配置所需工具。技能不是工具安装器，不保证招募人数、连续测试达标或审核通过。**

## 能做什么

- 先理解产品和测试目标，再形成准确的介绍与邀请。
- 在用户选择的 Google Groups、Reddit 社区寻找开发者，按作者去重。
- 区分邀请、同意、入群、Play 参加、自述安装、真实启动和功能试用。
- 获授权后使用真实 Android 手机做有限测试，保存干净截图，发送具体反馈。
- 按用户选择的间隔和执行模型监控新回复，维护本地去敏记录。
- 跟踪人工持续使用、问题修复与复测；准备事实材料供后续申请交接。

## 安装和使用

也可通过 skills CLI 安装（该第三方工具默认有安装遥测，介意时设置 `DISABLE_TELEMETRY=1`）：

```sh
npx skills add peikuo/play-closed-test-recruitment --skill play-closed-test-recruitment --agent codex
```


将本仓库作为一个完整技能目录安装到 Codex 的 skills 目录。若已有同名安装，请先比较和合并，避免覆盖本地修改。

```sh
git clone https://github.com/peikuo/play-closed-test-recruitment.git ~/.codex/skills/play-closed-test-recruitment
```

在支持技能的 Codex 环境中调用：

```text
使用 $play-closed-test-recruitment 帮我推进闭测招募。
先了解我的项目和测试目标，再确认渠道、工具与授权。
定时检查的间隔由我选择，真实安装和试用分别记录。
```

普通 GPT 聊天不一定能自动加载技能或控制浏览器、手机。Claude Code 使用者可以参照其当前官方技能安装方式自行实验；本项目没有做 Claude 端到端验证。

## 工具要求

| 工作 | 所需能力 |
|---|---|
| 产品理解、记录 | 相关文件读取、本地文件写入 |
| 公开候选与政策 | 网页搜索或网页读取 |
| 群、评论、私聊、Console | 用户授权的登录浏览器或适用连接器 |
| 安装、启动、截图、有限试用 | 用户连接并授权的真实 Android 设备，如 ADB |
| 定时检查 | 宿主调度器、可访问所需环境的执行器 |

缺少某项工具时，技能只能完成对应的分析、草拟或人工指导；不能声称外部动作完成。定时检查可选宿主支持的低成本模型，间隔、范围和通知条件由用户确定。

## 网站范围

主要使用 Google Groups、Reddit 的 AndroidClosedTesting / AndroidAppTesting / TestersCommunity 社区、指定 Reddit 私聊、具体 Play opt-in/商店页、自家应用只读 Play Console，以及 Google Play 官方帮助文档。

完整入口和限制见 [工具、网站与兼容范围](references/tools-and-compatibility.md)。网站清单不是默认操作授权，也不是网络沙箱。第三方链接不能扩大权限。

## 隐私与人的参与

- 发布包只包含通用规则和匿名案例，不包含真实联系人名单、成员邮箱、私聊、手机截图或后台记录。
- 运行记录放在用户选择的本地私有目录；不要同步到公开仓库。截图发送前检查通知、账号与个人内容。
- 在线模型处理不等于本地离线处理；提供给模型的内容也需要最小化和去敏。
- 用户负责设备连接、验证/协议/敏感权限，以及持续自然使用和体验判断。AI 短测不能替代这些工作。
- 不交换评分、不虚构测试、不批量群发、不修改发布配置、不许诺审核通过。

## 文件结构

```text
SKILL.md
agents/openai.yaml
references/
  tools-and-compatibility.md
  coordination.md
  participation-audit.md
  case-study.md
```

从 [SKILL.md](SKILL.md) 开始；参考文件按任务需要加载。`agents/openai.yaml` 仅为 Codex 界面元数据。

## 验证与限制

文件结构与参考路径已校验，发布内容经过隐私残留检查和独立 Astra 审阅，关键场景做过规则推演。实际案例覆盖招募、入口协调、部分设备短测、反馈发送和定时检查；不代表完整 14 天参与及最终生产审核已经验证。

执行时重新核对 [Google Play 官方要求](https://support.google.com/googleplay/android-developer/answer/14151465)和该账号 Console。人数门槛、账号适用范围及政策可能变化。

## 改进和问题反馈

欢迎通过 Issues 提交问题、去敏的失败场景或改进建议。请包含实际操作、预期结果、实际结果，以及宿主和可用工具；不要附邮箱、账号令牌、私人消息、成员表或未经去敏的截图。

修订后应重新检查授权边界、隐私、证据归因、引用路径和打包内容。本项目使用 [MIT License](LICENSE)，允许使用、修改与分发，须保留版权及许可证声明。

## 本地维护

开发者可把仓库保存在任意本地目录，再将 `~/.codex/skills/play-closed-test-recruitment` 软链到仓库目录，避免维护两份副本。这只影响本机技能发现，不需要把 GitHub 仓库软链到任何市场。替换已有技能前先比较并备份；软链指向必须仍可访问。用户按上面的 clone 安装也可正常使用，无需软链。

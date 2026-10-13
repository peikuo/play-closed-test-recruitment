# 协调记录与消息示例

用户参与与定时任务审计见 [participation-audit.md](participation-audit.md)。

## 最小记录结构

每个联系人一条，不按帖子重复建立。第一次运行由用户选择本地私有记录目录；不要放在默认同步到云端或公开仓库的目录。配置只存链接和去敏协调摘要，不写登录密码或浏览器会话。用户结束任务时提供保留/清理选项，删除按宿主授权规则执行。记录公开作者标识、应用、原帖/我方消息永久链接、群与opt-in链接、免费/语言/资格条件、用户特定限制，以及：

- 邀请发布与直接回应的核实时间。
- 对方入我方群、对方自述Play参加/安装/使用及各自证据级别。
- 我方入群、opt-in、安装、启动、功能试用各自状态与时间。
- 本地真实截图路径、反馈发送链接/时间、附件是否发送成功。
- 未解决问题、下一步、最后成功核实时间、最近尝试检查时间/范围。

没有证据用 unknown，不默认 false。只保存协调事实的摘要，不存私信原文、成员邮箱、账号令牌或完整私聊截图。统计汇总要同时保留数据来源、是否含自己、是否下限、检查时间；跨渠道相同作者有证据才能合并。

## 简短例句

邀请：
> Hi [name], would you like a free one-for-one test exchange: [their app] for [our app]? [Truthful current status]. Group: [group]. Test: [opt-in]. Please let me know once you join and opt in. Thanks, [sender].

反馈：
> I installed [app/version] and opened [screen] on [device]. I tried [action]; [observed result]. I haven't tested [remaining feature]. Here is a real screenshot. [For bugs: steps, expected result, actual result].

链接异常：
> [Exact page error] appears after [step]. Could you send the full group and opt-in links and confirm the supported region/device? I haven't been able to install it yet.

身份未匹配：
> Could you confirm whether you joined [our app] and opted in? I cannot yet match your membership. Your Google Groups display name is enough; no email is needed publicly.

例句需适配实情，不自动许诺未获用户确认的每天频率、日期或完整14天服务。

## 常见故障

- App not available：核对同账号、群资格、opt-in、地区和发布可用性，先问准确错误。不要未经授权改自家发布配置。
- Device incompatible：核对真实型号、Android及架构。64位版本不能假设32位手机可用；告知限制，不把不能安装标为完成回测。
- 链接被截断：请求完整URL，不猜群名。
- 公开帖子被过滤：单次核实页面状态，按用户授权换合适公开评论/私聊渠道，不批量重复发帖。
- 私聊遗漏：只读公开评论不覆盖聊天。用户指出私聊时去指定对话核实；不把给别人回复当成对我方回应。
- 文件上传：以已显示的新消息和附件为准。预览或上传控件超时不是成功；保留真实本地文件，询问合法替代接收方式。
- 人数波动：达标不等于连续14天完成，不编造倒计时。保留缓冲并整理实际参与与反馈。
- 监控成本：只检查相关新回复/成员变化，按需轮换范围；用短基线恢复，不把长聊天重放给每次检查。无变化无通知。

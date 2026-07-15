# Cocos Doctor

Cocos Doctor 是一个面向 Cocos Creator 3.8.x 的 evidence-first Inspector。它帮助开发者排查节点不显示、Button 点不到以及 Layout / Widget 异常，并把结论建立在可核对的场景证据上。

> 当前状态：closed Alpha。这个仓库是公开的产品、文档、安全与反馈入口，不是开源源码仓，也暂不提供公开安装包。

## 它坚持什么

- 先展示证据，再解释结论。
- 修改前先展示精确 Preview。
- 只允许狭窄、类型化的安全操作。
- Apply 后重新采证；可恢复的操作必须支持明确 Undo。
- 证据不足时报告缺口，不猜测设计意图。
- 默认不上传项目、场景或诊断数据。

当前 Alpha 的验证基准为 Cocos Creator 3.8.8。请勿把 Alpha 安装到生产项目；任何受邀试用都应使用隔离的一次性工程。

## Alpha 参与和反馈

本轮计划邀请最多 8 位成年 Cocos Creator 开发者完成一次约 20–25 分钟的盲测。报名条件、隐私边界和参加方式请见 [Cocos Doctor closed Alpha 招募](https://github.com/jingyuyan19/cocos-doctor/discussions/1)。如果准备参加盲测，请不要先观看完整演示。

目前不在 GitHub 公开分发 Alpha ZIP。GitHub 招募公告是主入口；[Cocos 中文社区主题](https://forum.cocos.org/t/topic/176550) 仅用于背景和备用通知。请不要在公开 Issue、Discussion 或论坛回复中留下手机号、邮箱、微信号、商业项目文件或包含凭据的日志。

- 普通问题与可复现 Bug：使用 GitHub Issues。
- 产品想法与使用讨论：使用 [GitHub Discussions](https://github.com/jingyuyan19/cocos-doctor/discussions)。
- 安全问题：遵循 [SECURITY.md](SECURITY.md)，不要公开漏洞细节。
- 隐私边界：[PRIVACY.md](PRIVACY.md)
- 兼容范围：[docs/compatibility.md](docs/compatibility.md)

## English

Cocos Doctor is an evidence-first Inspector for Cocos Creator 3.8.x. It is currently a closed Alpha. This public repository hosts product information, safety documentation, release notes, and community feedback; it does not currently publish the product source or an installable Alpha package.

The current blind Alpha study is recruiting up to eight adult Cocos Creator developers. See the [Alpha recruitment discussion](https://github.com/jingyuyan19/cocos-doctor/discussions/1) before watching the full demo. Do not post commercial project files, personal contact details, credentials, or sensitive logs in public Issues or Discussions.

## 独立产品声明

Cocos Doctor 是由 VberAI 独立开发的第三方工具，不隶属于 Cocos，也不代表 Cocos 官方。Cocos、Cocos Creator 及相关标识归其各自权利人所有。

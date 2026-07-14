# Architecture Overview

Cocos Doctor 的公开架构原则可以概括为：

```text
Cocos Creator scene evidence
  → normalized evidence package
  → deterministic diagnosis
  → findings, confidence, and evidence gaps
  → optional narrow previewed operation
  → recapture and verification
  → explicit recovery when supported
```

核心边界：

- AI 可以解释结果，但不拥有任意场景写权限。
- 诊断必须能引用具体证据；缺少关键能力时显式降级。
- 修改接口必须是可验证的狭窄类型，而不是脚本执行器或任意属性入口。
- Preview 不修改场景；Apply 与 Undo 后都重新采证。

当前仓库不发布产品实现源码。未来若开放稳定的数据协议或验证器，它们会在对应目录附带独立许可证和版本承诺。

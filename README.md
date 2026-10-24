# TagTuner — 需求验证页（公开小仓）

本地 Etsy listing SEO 审计工具的公开需求验证页。MVP 源码（`audit.py` 等）只在本地私有目录
`~/workspace/independent/etsy-seo-audit/`，不进本仓。

- 验证页：https://alapha888.github.io/tagtuner-waitlist/
- MVP 状态：已构建并测试（19 项规则检查、5 维度加权、5 个真实 listing 样本可复现，见私有目录 README），尚未公开发售。
- 判定线（2026-10-24 定）：2026-10-30 前登记 ≥10 → Gumroad $19 一次性上架并通知登记者；＜5 → 关线并邮件通知登记者。价格与门槛均为验证参数，不是市场结论。
- 登记机制：页面结构化 mailto 按钮（主题 `[TagTuner] Notify me on launch`），页面不显示裸邮箱地址。
- 需求证据：在位者 eRank（免费版＋$5.99/$9.99/$29.99/月）与 Marmalead（$19/月起、无免费版）均为订阅制关键词研究工具；本品切口=本地运行不上传数据＋$19 一次性买断＋诚实"规则审计"（不做搜索量估算）。

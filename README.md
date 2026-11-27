# William DTC 落地页蒸馏包 — 打包说明

## 包里有什么

- `batches/batch-01/` 至 `batches/batch-10/`：10 批原始材料，共 **251 条**推文记录（250 条新收 + 1 条补收）、**224 张**设计图
  - 每批一个 `README.md`：每条推文的摘要、发布日期、推文链接、点赞/转发/回复/浏览数、原图链接、图里是什么设计（摘要改写，不是推文全文转载）
  - 每批一个 `images/`：下载到的原图，按汇报顺序编号命名
  - 时间范围：2026-09-06 至 2026-11-25（另有 2026-10-03 置顶帖原版在第七批）
  - 来源：X @williamdtc2y（William | DTC Landing Page Designer & Dev）
- `skill-draft-v04.md`：本机 Muse 做的蒸馏（v0.4），225 条全并入，验收表 B 共 18 项
- `WORKFLOW.md`：工作流——先做图，再按图做站
- `AGENT-HANDOFF.md`：给另一个 Agent（Antigravity / Gemini 4）的交接任务书

## 数据口径

- 225 条是设计相关推文，不是该账号全部发帖。账号当时共 494 条帖子，未收的 2026-09-06 之前部分在第十一批继续补（只补新模板）。
- 重复设计按原样逐条记、没有合并，README 里注明了重复关系（MELAO 发了 3 次、ZYN 发了 3 次、Glutatrix 发了 3 次、EverPaw、MAV 胶原蛋白 Listicle、蓝莓 Listicle 等反复出现）。
- 缺图缺价如实记了，没编：第五批第 11 条男装帖外链已失效、图丢了；第七批第 7 条文案写 TERRAL、配图实际是 Osasuna，以图为准。
- 第九批跳过 1 条静态广告概念帖（2026-09-16，22 赞、591 浏览），第十批已补收（EverPaw 静态广告概念，见 batch-10 第 0 条）。第十批 25 条新模板只作原始材料，尚未并入 v0.4（待 v0.5）。

## 怎么用

1. 拿去给 Antigravity / Gemini 4 蒸馏：把 `AGENT-HANDOFF.md` 当任务书发给它，`batches/` 是原始材料。
2. 本机 Muse 的蒸馏在 `skill-draft-v04.md`，可以拿两边结果对照：结构、规律、验收表哪里一致、哪里不一样，不一致的地方以原图为准核对。
3. 正式 skill 在本机：`~/workspace/custom-skills/william-dtc-landing-page/SKILL.md`（内容与 v0.4 一致，参考图精选 27 张在 `assets/reference/`）。

# William DTC 落地页蒸馏 Skill — 草稿 v0.4（2026-11-27，第九批并入）
来源：@williamdtc2y 第一–九批共 225 条（`batch-01/` 至 `batch-09/README.md`，第九批止于 2026-09-16，图 201 个文件已下载在各批 images/；第九批 25 张）
营销底座：Corey Haines marketingskills（`local-marketingskills/`：cro、marketing-psychology、copywriting、offers、pricing、image）+ `local-shopify-cro` + `local-shopify-product-page`
工作流：先做图，再按图做站。图是蓝图，不是终稿。

## v0.4 对 v0.3 的改动（先说这个）
- **第九批并入**：25 条（2026-09-22 至 2026-09-16），九批合计 225 条、图 201 张。新增规律 10 条，见下面 A/B 节与验收表 B（16 项 → 18 项）。
- **设计是增长杠杆**：目标不是让页面“更好看”，是让更多访客理解 offer、信任产品、采取行动、多买（第九批 Every Day Almonds，`batch-09/01-everyday-almonds-ba-v2.jpg`）。
- **订阅/复购单列一条**：产品页不应该在第一次购买就停下（第九批 BOOST，`batch-09/02-boost-muscle-brain.jpg`）——1/2/3 包装、清晰“Best Value”、订阅省钱、灵活配送、评价、保证 + 配送保障，offer、定价、购买选项和产品同样重要。
- **PDP 旅程 8 节**（第九批 Perfect Lemon，`batch-09/08-perfect-lemon.jpg`）：产品 → 好处 → 评价 → 包装尺寸 → 订阅 → 保证 → FAQ → 经常一起买，每节在客户问之前先回答一个问题。
- **Listicle 旅程定为好奇 → 信任 → 渴望 → 行动**（第九批 Soursop，`batch-09/07-soursop-listicle.jpg`）；**Advertorial 先教育**（第九批蓝莓能量饮料 Advertorial 静态长图版，`batch-09/09-blueberry-advertorial.jpg`，与第七/八批视频版同一设计）。
- **价格锚点与决策点可见**：价值递进要显而易见（1 包试试 / 2 包最热门 / 3 包最值，第九批 Berrylicious）；重要信息要在做决定时可见，6 项（它是什么、为什么重要、里面有什么、选哪个选项、省多少、为什么能信，第九批 Gaplu，`batch-09/14-gaplu-ragi-malt.jpg`）。
- **移动端首页只有几秒**（第九批 Choco Bites，`batch-09/12-choco-bites-homepage-ba.jpg`）：Before 通用标题、视觉层级弱、产品靠后、信任信号有限；After 产品优先、视觉层级清晰、好处立刻可见、首屏口碑、CTA 更有说服力。
- **口径说明**：第九批跳过 1 条静态广告概念（2026-09-16，22 赞、591 浏览），浏览器按收录范畴判定不在里面；但第八批第 9 条 SLIQ 宠物护理静态广告曾收录过，同类内容口径不一致，如需补收可下一批说明。重复提示：ZYN（1–12 号标注版）、Glutatrix、Raw Honey、EverPaw、Glanora 在第九批再次出现，William 的模板复用率极高，新规律收益已明显递减——225 条已够蒸馏，第十批起只补新模板，不再逐批全并。

## v0.3 对 v0.2 的改动（保留）
- **v0.2 留的口子补上了**：Listicle / Advertorial 不再是“待第二批补”，第五–八批给齐了完整结构（见 B 节 Listicle、Advertorial 两条），Listicle 是 William 讲得最多的第二类模板，仅次于购买框。
- **信息顺序升为铁律**：同一套顺序在第六批（HerbTonics）、第七批（ALLHEALTH365）、第八批（CANADA POOCH 平行版）出现三次以上，William 自己重复发——skill 里不再当建议写，当验收铁律。
- **新增验收门**：产品页 3 件事速查、买家落地 5 问、Hero 6 项、购买框独立成交、对比表必备、移动端决策点可见，全部进验收表 B。
- **品类规则扩了**：宠物 7 问、礼品泰迪熊/毛绒套装结构、高客单价 5 问、新品类先讲“怎么用”、测验（Quiz）解法、静态广告 6 步流程。
- **仍待定（v0.3 时）**：v0.2 说的“用一个新产品走一遍 1–6 步全流程验证 v0.2 是否落地”还没做，等 Bill 定产品；第九批当时还没抓。v0.4 已并入第九批，验证仍待定。

## v0.2 对 v0.1 的最大修正（保留）
**v0.1 错了：不能让 Nano Banana / ChatGPT 生一整页带文字、价格、星级、套装的图。**
image skill + Shopify 产品页的身份锁都明说：模型渲染不好段落文字、数字、UI，logo/文字要后加；参数图、包装清单图是排版规格，不是生图 prompt。整页 prompt 动辄 200+ 词，必然失焦、编字、飘。这正是以前生图不到位的地方。
**v0.2 改成：生图只生视觉资产，文字、价格、图标、尺寸全部在代码里排。**
- 生图产出：Hero 产品照、生活场景、前后对比、包装特写，分开生。
- 代码产出：版式、文字、价格、星级、套装、CTA、信任条、FAQ、保证，全部用代码写。
- 图里文字 ≤ 5 个词，不渲染价格、星级数字、套装金额、倒计时、库存数字，不编造品牌名、评价数、结果数据、认证。

## 生图前置必填表（先填表，再写 prompt，缺项标 [待补]，不许编）
1. **产品真相表**：产品名、品类、用途、目标客、已批准主好处、功能/规格、材质/成分、用法、变体、价格货币、库存、物流、退换、保修/保证、已批准证明、受限声明，每条事实有来源。缺的列 gap 清单，绝不编造成分、规格、认证、效果、评价、紧迫性、库存、物流、保证、结果。
2. **价值公式四杠杆打分**（1–10 分，最低分先补）：梦想结果 × 实现可能性 /（时间延迟 × 付出/牺牲）。梦想结果要具体到感官；可能性靠证明+方法论+保证；时间延迟压缩（首个可见效果 Week 1、3 步上手）；付出降低（3 步流程、免邮、随时取消订阅）。
3. **身份锁表**：轮廓/尺寸/颜色 hex/材质/按钮位置/must_not_change 清单，逐字进 prompt 负面清单。换产品时包装不能变形。
4. **品类判定**：补剂 / 宠物 / 礼品（含泰迪熊/毛绒） / 护发美妆 / 高客单价 / 服装配饰 / Listicle / Advertorial。先定品类再定页面重点：护肤讲成分、补剂讲信任、宠物讲品质、电子讲功能（第五批六宫格总纲，`batch-05/03-six-category-pdp.jpg`）。
5. **参考图编号**：从下面映射表挑最接近的一张。**同模板不同产品要分开记**：模板按结构记，不按产品记（第八批：Bio Magic 有机肥与 ENERGI 接骨木莓软糖用同一购买框模板）。

## A. 不变的（所有产品通用）
- 产品页只有一个任务：去掉购买犹豫。买家还要自己想“为什么需要 / 为什么信你 / 有什么不同 / 到底买到什么”，就是页面在让他费劲（第七批 AURORA WEAR 置顶帖原版，34 赞、1,856 浏览，八批以来单条最高，`batch-07/08-aurora-wear-pinned.jpg`）。
- **产品页 3 件事速查**（第五批 William 自己的验收口径）：5 秒说清它是干什么的吗；价格加套装不用滚动就清楚吗；Add to Cart 附近有证明吗。缺一个就是漏单。
- **买家落地 5 问**（第六批）：这是什么、为什么我要它、能信吗、该选哪个、为什么现在买。PDP 按兴趣、信心、选择、购买引导排，不是只摆一张漂亮图。
- **信息顺序是铁律**：先给价值 → 建立信任 → 把 offer 讲清 → 去掉异议 → 让下一步显而易见。顺序错了内容再全也没用。平行版（第八批 CANADA POOCH）：问题 → 好处 → 证明 → offer → 购买。**修法不是加内容，是按顺序排信息**：信息全对也会让购买变难，错在顺序，不在数量。
- 标题公式（二选一）：`{结果} in {时间}` 或 `{结果} without {痛点}`，必须过两道测试：
  - “Now you can”测试：前面加 Now you can，读起来是具体新能力才算过。
  - Human Action Model：当前不适 → 更好愿景 → 行动路径，三拍缺一不可。
- **Hero 6 项验收**（第七批 CeraVe，`batch-07/24-cerave-hero.jpg`）：产品定位、好处立刻可见、强视觉证明、首屏上口碑、一个清晰 CTA、信任做到首屏里。
- **购买框要能独立成交**（第六批 Replo 新购买框，`batch-06/17-replo-buybox-cover.jpg`）：套装、动态价格、订阅、一次性、支付加配送、FAQ、Sticky Add to Cart 全在购买框里，买家不用离开购买框就能决定。
- 购买框 9 步，顺序不可调：
  1. 星级 + 评价数，紧贴标题下（具体数字，如 4.8/5（2,347 reviews），不要“好评如潮”）
  2. 一句话好处（过上面两道测试，不是成分堆砌）
  3. 选择器（按品类：尺寸/颜色/烘焙度/体重，写清每档用量 + 能用多久）
  4. 套装 3 档 Good–Better–Best，中间档 MOST POPULAR / BEST VALUE，省 $ 和 % 双写，写 $/单位（$/颗、$/天、每袋能用几天），顶档约 2–3× 首档
  5. Subscribe & Save，预选或高亮，写清省 %、对比一次性价、随时取消/跳过；不要两个折扣叠在一起让用户算
  6. 主 CTA 一个，动词+得到什么+价格（ADD TO CART – $32.95），颜色全页最跳，Shop Pay 等次按钮不能抢主按钮
  7. 按钮旁三选一：免邮门槛（Add $28.76 more for free shipping）/ 真实截止日（For Christmas, order by Dec 17）/ 保证天数
  8. 信任条 3–4 项，图标+短词：免邮 / 退换 / 安全结账 / 产地 / 检测，放 CTA 附近
  9. 具名评价 1 条（名字 + 身份/场景 + 具体结果）+ 折叠栏 Description / Benefits / What's Included / How to Use
- **对比表不是可有可无，是必需品**（第八批蘑菇咖啡，`batch-08/02-mushroom-coffee-table.jpg`）：用户不读、只扫，涉及选择就要对比表。自家 vs 传统/竞品，勾叉两列，7 行以内。减少决策疲劳、靠透明建立信任、有信心的用户会转化。
- **客单价不应该以牺牲转化为代价**（第八批 Air Jordan）：先让第一次购买感觉容易，再给相关理由多加。“You may also like”加购放在购买决定之后，不是之前。
- **桌面好看不算完，移动端才是真考**（第八批 TroPexl 褪黑素）：桌面给你空间解释，移动端逼你排优先级。两端都要保持关键决策点可见：产品价值、好处、评价、订阅省钱、一次性购买、加购、配送加保证。数字口径：移动端版式没优化丢 70% 付费流量，版式摩擦丢 60%（第六批 CHEWY BLISS 一条）。
- **设计是增长杠杆，不是更好看**（第九批 Every Day Almonds，`batch-09/01-everyday-almonds-ba-v2.jpg`）：目标不是让页面“更好看”，是让更多访客理解 offer、信任产品、采取行动、多买。更高转化率从同样流量里拿更多买家，更好 offer 结构 + 聪明加购拉客单价，同样流量赚更多收入才是真正的 Before → After。
- **产品页卖的是决定**（第九批 FLOW FUEL，`batch-09/15-flow-fuel-bundle.jpg`）：产品页不应该只卖产品，要卖决定。产品好处放前面、多个购买选项、套装省钱清晰、评价和信任信号、配送 + 保证保障、强而可见的 CTA。offer 容易理解，购买旅程也变容易。
- **好设计呈现的是 offer**（第九批 Grand Taste 姜黄粉，`batch-09/16-grand-taste-turmeric.jpg`）：一个产品，三种买法。offer 不应该让客户自己算账：1 包 → 试试 / 2+1 → 省更多 / 3+2 → 最值。加清晰定价、产品好处、评价、信任信号，购买决定就好走得多。
- **重要信息要在做决定时可见**（第九批 Gaplu，`batch-09/14-gaplu-ragi-malt.jpg`）：客户不应该滚完整页才理解自己在买什么。6 项在决策点可见：它是什么、为什么重要、里面有什么、选哪个选项、省多少、为什么能信这个品牌。目标不是加更多信息，是让对的信息更容易找到。
- **价格锚点：价值递进要显而易见**（第九批 Berrylicious，`batch-09/13-berrylicious-jam.jpg`）：不要给 3 个几乎一样的选项，1 Pack → 试试 / 2 Pack → 最热门 / 3 Pack → 最值。客户不应该自己想明白哪个选项合理，好电商 UX 让价值好比较。
- **移动端首页只有几秒**（第九批 Choco Bites，`batch-09/12-choco-bites-homepage-ba.jpg`）：移动端没有犯糊涂的空间。Before 通用标题、视觉层级弱、产品靠后、信任信号有限；After 产品优先、视觉层级清晰、好处立刻可见、首屏口碑、CTA 更有说服力。移动端首页只有几秒讲清为什么值得继续滑。
- **PDP 旅程 8 节**（第九批 Perfect Lemon，`batch-09/08-perfect-lemon.jpg`）：好产品页不只是首屏，是客户说“我感兴趣”之后发生什么。顺序：产品 → 好处 → 评价 → 包装尺寸 → 订阅 → 保证 → FAQ → 经常一起买。每节在客户问之前先回答一个问题。好 PDP 不只是呈现信息，是引导购买旅程。
- 完整落地页顺序：Hero → 社会证明条 → 问题/痛点 → 方案/好处（3–5 条）→ How It Works（3–4 步）→ 异议处理（FAQ/对比/保证）→ 终 CTA。
- 完整首页顺序：顶部套装优惠 → Hero → 真实效果+数据 → 好处 → 评价 → 对比表 → FAQ → 保证收尾。
- 视觉：单品主色贯穿全页（取自包装 hex），桌面+移动并排展示，Before 用红色编号标注问题，After 干净留白。**素拍 vs 生活场景**（第六批 Hilma，`batch-06/06-hilma-ba.jpg`）：空白背景瓶子只告诉长什么样，生活场景照帮买家想象自己在用。
- Before 常见毛病清单：无价格、无星级、首图有别家品牌、卖点埋在文案里、折扣叠加、套装埋得深、No reviews yet 放按钮下、内部备注上线、颜色只用文字、大文字徽章遮住照片、倒计时没折扣、9999+ in stock。
- **禁语 / 禁行为**：禁“100% guaranteed”无条件、Secret、Game-changing、Limited time（无真实期限）、假倒计时、假库存；不编造事实；不从 Before→After 推断因果、不写任何转化提升承诺（无测试证据）。
- **文案和配图对不上也要如实记**（第七批）：有一条文案写的是 TERRAL，配图实际是 Osasuna（`batch-07/07-osasuna-sulforaphane.jpg`），品牌、产品名、价格必须以图为准核对，不能只信文案。第五批第 11 条男装帖图丢了（pic.x.com 外链已失效），设计内容没法确认，文件里如实记了，没编——同理，缺图缺价时标 [待补]，不许编。

## B. 按品类变的（条件规则）
- 补剂/食品粉：订阅方案卡（月/3 个月/6 个月，省 16%/24%/30%）、对比表（本品 vs 普通款）、好处标签 3 秒看懂。**13 节产品页是补剂的上限模板**（第五批头发维生素）：套装、订阅、价格实时更新、对比表、评价、FAQ、Sticky 购物车加免邮横幅。**订阅三件套反复出现**（第五批 10 月 12 日四条连发都是订阅主线）：默认选中、大方案省 25%、订阅再减 15%、免邮绑 2 瓶以上、随时取消。NAKED HARVEST 第三次出现，37 赞、1,024 浏览，五批以来单条最高浏览——“每瓶价”是 William 自己最看重的模板，订阅价必须写 $/瓶。
- 宠物：体重/体型选择器（<10kg / 10–20kg / 20–40kg / 40kg+），每档写每天用量 + 一袋能用多久；评价写宠物名字。**宠物页 7 个问题**（第八批 Alvar Pet，`batch-08/03-alvar-pet-ba.jpg`）：给谁的、帮什么、有什么不一样、选哪个尺寸、有没有更值的套装、能信吗、买完之后会怎样，按这 7 问验收。
- 礼品（项链/礼盒）：价格旁列盒内全部内容、卡片实时预览、可选留言、为什么值这个价。**礼物类卖感觉和决定**（第七批 WarmHugs 泰迪熊，`batch-07/22-warmhugs-teddy.jpg`）：展示使用中的产品、情感好处、关键功能、评价、offer、去掉配送顾虑，礼物类按这个顺序，不是按补剂那套。**泰迪熊/毛绒玩具单列套装结构**（第八批 KAWAII 粉彩泰迪熊）：Purple Bliss、WarmHugs、KAWAII 三款泰迪熊设计都不同，礼物类泰迪熊是 William 反复做的品类。
- 护发/美妆：前后对比照、按周效果时间线（Week 1 / 4 / 8）、三步使用流程、造型师/专家评价。
- 高客单价（£299 LED 面罩类）：参数放顶部、保修、分期、本地配送写按钮下。**高客单价也要去掉犹豫**（第七批 LeRoy 鳄鱼皮穆勒鞋，`batch-07/14-leroy-mules-cover.jpg`）：是真的吗、舒服吗、尺码准吗、评价能信吗、不合身怎么办——高客单价不是少写信任，是多写 5 个具体问题。
- 服装/配饰：颜色用色块不是文字、尺寸用英寸、轮播带缩略图、真实配送时间放按钮旁。
- **新品类、陌生品先答“怎么用”**（第七批 T-POPS，`batch-07/03-t-pops-makhana.jpg`）：吃法创意区先于销售，在购买框前加“怎么用、怎么吃、怎么搭”一节。
- **测验是选择困难的解法**（第五批 HUSH & HAVEN）：问 4 个问题只推荐一件被子，98% match，还告诉你为什么适合。SKU 多、难选的品类用测验代替陈列。
- **订阅/复购：产品页不应该在第一次购买就停下**（第九批 BOOST，`batch-09/02-boost-muscle-brain.jpg`）：1、2、3 包装选项、清晰的“Best Value”选择、订阅省钱、灵活配送、评价口碑、保证 + 配送保障。产品只是等式的一部分，offer、定价、购买选项同样重要。订阅三件套（第五批）仍然适用：默认选中、大方案省 25%、订阅再减 15%、免邮绑 2 瓶以上、随时取消；订阅价必须写 $/瓶。
- **Listicle（冷流量的必经站）**：结构固定——痛点理由逐条导向产品 → 对比表 → 最后 offer box。Gymshark 8 理由、KENOFOR 10 理由、蓝莓 10 理由、Unfabled 5 理由，结构都一样。广告直接跳产品页就是跳过这一步。MAV 胶原蛋白 Listicle 发了 3 次（静态图、0:38 视频、0:24 视频，`batch-06/21-mav-collagen-listicle.jpg` / `23-mav-collagen-cover.jpg` / `25-mav-collagen-cover-v2.jpg`），同一设计三种形式——Listicle 是 William 讲得最多的第二类模板，仅次于购买框。**Listicle 的旅程是好奇 → 信任 → 渴望 → 行动**（第九批 Soursop，`batch-09/07-soursop-listicle.jpg`，12 理由长图 + 对比表 + 限时 50% OFF）：信息多不等于卖得多，结构才等于。好处更清晰、证明更强、摩擦更少、购买路径更清晰。
- **Advertorial（冷流量的桥）**（第八批橙色去角质凝胶）：广告 → Advertorial → 产品页 → 结账。Advertorial 介绍问题、教育客户、解释产品、展示好处、用证明建立信任、处理异议、引向产品页。冷流量不要直推产品页，先过 Advertorial。**Advertorial 先教育、再让购买感觉理所当然**（第九批蓝莓能量饮料 Advertorial 静态长图版，`batch-09/09-blueberry-advertorial.jpg`，与第七/八批视频版同一设计）：产品不总需要再打折，需要更好买的理由。强标题和清晰角度、“5 个理由”结构、推销之前先讲清产品好处、关键卖点之后放口碑、结尾清晰 CTA 和紧迫感。**标准页卖功能，高转化页处理异议**（第六批 CHEWY BLISS，`batch-06/12-chewy-bliss-landing.jpg`）：口碑先行、按周预期、价值锚点对比表、1 到 10 包数量档。
- **静态广告也有流程**（第八批 SLIQ 宠物护理）：产品是什么、解决什么问题、关键好处、怎么运作、怎么用、口碑——6 步：停下滚动、解释价值、产生足够兴趣去点。静态广告不是一张好看图，是 6 步流程。

## C. 按产品变的（每次填空）
主色 hex（取自包装）、Hero 主体、产品名、价格/原价/省多少、套装 3 档、评价数/星级、卖点 3–4 条、保证天数、免邮门槛、截止日、产地/检测。

## 参考图映射（生图时指定一张，注明编号 + 机制）
- 16-scrumpy-joint.jpg：移动购买框 Before→After，宠物范本。机制：默认效应（订阅预选）+ 目标梯度（体重选择器显示能用多久）+ 对比效应。
- 11-ametoz-d3k2.jpg：补剂购买框。机制：订阅 + 免邮门槛 + 信任条。
- 07-my-wife-love-knot.jpg：礼品购买框。机制：盒内清单 + 真实截止日。
- 01-allhealth365-vitamin-c.jpg / 04-biome-fiber.jpg / 09-potira-coffee.jpg / 10-naked-harvest-matcha.jpg：完整 PDP。04 是套装锚定最佳范本。
- 21-melao-rosemary-landing.jpg：完整落地页，浅绿三栏全页拼贴。机制：每板块先答一个顾虑。
- 24-verdana-greens-homepage.jpg：首页，深绿 Hero + 绿粉爆炸。机制：锚定 + 社会证明 + 保证收尾。
- 25-aurora-wear-pinned.jpg：置顶方法论，薰衣草紫 PDP。
- 第五批新增：`batch-05/03-six-category-pdp.jpg` 品类六宫格总纲；`batch-05/01-jaggery-powder.jpg` 少想多买（套装 1/2/3 包 + 评价放图库旁 + 保证放按钮下）。
- 第六批新增：`batch-06/17-replo-buybox-cover.jpg` 购买框独立成交范本；`batch-06/12-chewy-bliss-landing.jpg` 高转化页处理异议范本；`batch-06/21-mav-collagen-listicle.jpg` Listicle 三形态之一。
- 第七批新增：`batch-07/08-aurora-wear-pinned.jpg` 去掉购买犹豫总纲（八批最高 1,856 浏览）；`batch-07/24-cerave-hero.jpg` Hero 6 项范本；`batch-07/22-warmhugs-teddy.jpg` 礼物类顺序范本。
- 第八批新增：`batch-08/01-canada-pooch-ba.jpg` 按顺序排信息范本；`batch-08/02-mushroom-coffee-table.jpg` 对比表必备范本；`batch-08/03-alvar-pet-ba.jpg` 宠物 7 问范本。
- 第九批新增：`batch-09/01-everyday-almonds-ba-v2.jpg` 设计是增长杠杆范本；`batch-09/02-boost-muscle-brain.jpg` 订阅/复购范本；`batch-09/07-soursop-listicle.jpg` Listicle 好奇→信任→渴望→行动范本；`batch-09/09-blueberry-advertorial.jpg` Advertorial 先教育范本（静态长图版）；`batch-09/08-perfect-lemon.jpg` PDP 旅程 8 节范本；`batch-09/12-choco-bites-homepage-ba.jpg` 移动端首页 Before→After 范本。

## 生图提示词模板（v0.2：分资产生，40–80 词）
### 模板 1：Nano Banana — 拿参考图改（优先，漂移最小）
```
Use the attached reference image as the layout blueprint. Keep the layout, section order, and buy-box structure exactly the same. Do NOT copy its product, brand, copy, or prices.
Replace with this product: [产品名 + 一句话是什么] / Packaging: [包装颜色/形状] / Main color: [hex]
Output: visual assets only, no text, no price, no stars, no numbers. Mobile-first, clean, no watermark, no invented brand name.
```
先给产品图，再给参考图。只生视觉资产，不生整页文字。

### 模板 2：ChatGPT — 从零生视觉资产（无合适参考图时）
```
Design visual assets for a Shopify [PDP / landing page] for [产品名], [定位].
Style: William DTC style — mobile-first, [主色] background, clean white cards, real product photo on top.
Assets needed: hero product photo with space for headline, lifestyle usage photo, before/after pair (same angle, same light), packaging close-up.
No text, no price, no logo in the image. 40-80 words in the prompt, specify size: [9:16 mobile buy box / 16:9 hero / reference ratio].
```
### 模板 3：分资产生（默认推荐）
Hero 产品照、生活场景、前后对比、包装特写分开生，每张过验图清单，再在代码里拼。模型分工：换产品/换色用 Nano Banana（多图参考：产品图 + William 参考图）；纯新视觉用 ChatGPT Images；文字多的徽章用 Ideogram（只放 3–5 个词）；品牌一致批量用 Flux 多图参考。

## 验图清单 A（生图 agent 自查，不过重生，最多 2 次）
- [ ] 主色与包装 hex 一致，包装轮廓/形状没变形（对身份锁表）
- [ ] 移动端优先，桌面+移动布局合理，无文字重叠、无编造品牌名
- [ ] 图里无价格、无星级数字、无套装金额、无倒计时、无库存数字，文字 ≤ 5 个词
- [ ] 前后对比同一角度、同一光线
- [ ] 尺寸/比例符合要求，图片 WebP、按显示尺寸裁、alt 文本

## 建站顺序（Codex / Antigravity，不可跳步）
1. 真相表 + 四杠杆 + 身份锁（缺项列 gap，不编）
2. 选参考图（按品类，注明编号）
3. 写文案 brief（标题过两道测试，CTA 按动词+得到什么+价格，FAQ 列异议清单，Bonus Stack：3–5 个，每个对应一个异议，总值 < 2× 主价）
4. 生视觉资产（分开生，每张过验图 A）
5. 代码拼页面（按 A 层顺序；所有文字、价格、图标、尺寸用代码写，图片只作视觉资产）
6. 验收表 B（独立验收，不许建站 agent 自己打勾）

## 验收表 B — 验站（v0.4：18 项）
- [ ] 每条产品事实能在真相表找到来源；评价、数据、认证真实且放对位置
- [ ] 价格/原价/省 $/省 %/每单位价全对，订阅价与一次性价对比正确（订阅写 $/瓶）
- [ ] 套装 3 档、MOST POPULAR 标记、Bonus Stack 全在
- [ ] 星级+评价数在标题下；具名评价带名字+具体结果；信任条 3–4 项在 CTA 附近
- [ ] 保证写清天数+条件，禁语为零
- [ ] 紧迫/稀缺有真实来源（日期/批次），假倒计时、假库存为零
- [ ] CTA 只有一个主按钮、颜色最跳、文案带价格；次按钮不抢主按钮
- [ ] FAQ 覆盖价格/适配/用法/不管用怎么办；对比表基准明确
- [ ] 移动端顺序 = 购买框 9 步顺序
- [ ] 不写任何 Before→After 带来的转化提升承诺
- [ ] **新增** 3 件事速查全过：5 秒说清是干什么的、价格+套装不用滚动就清楚、Add to Cart 附近有证明
- [ ] **新增** 信息顺序 = 价值 → 信任 → offer → 异议 → 下一步明显（或 CANADA POOCH 平行版），不是内容堆得多
- [ ] **新增** Hero 6 项全在：定位、好处立刻可见、强视觉证明、首屏口碑、一个清晰 CTA、首屏信任
- [ ] **新增** 购买框能独立成交：套装、动态价、订阅/一次性、支付+配送、FAQ、Sticky ATC 全在框内
- [ ] **新增** 涉及选择就有对比表：自家 vs 传统/竞品，勾叉两列，7 行以内
- [ ] **新增** 移动端关键决策点全可见：价值、好处、评价、订阅省钱、一次性购买、加购、配送+保证；用了 Listicle/Advertorial 时结构按 B 节走（理由逐条导向产品 → 对比表 → offer box；广告 → Advertorial → 产品页 → 结账）
- [ ] **新增（v0.4）** 重要信息在做决定时可见：它是什么、为什么重要、里面有什么、选哪个选项、省多少、为什么能信，6 项在决策点可见，不用滚完整页才明白
- [ ] **新增（v0.4）** PDP 旅程 8 节全在：产品 → 好处 → 评价 → 包装尺寸 → 订阅 → 保证 → FAQ → 经常一起买；订阅/复购选项清晰（1/2/3 包装、Best Value、订阅省钱、灵活配送），产品页不只卖第一次购买

## Agent 分工
| 角色 | 推荐 Agent | 输入 | 输出 | 禁止 |
|---|---|---|---|---|
| 策略/文案 | ChatGPT | 真相表、品类、参考图编号 | 填空、标题、CTA、FAQ、Bonus Stack、四杠杆打分 | 不编造评价/数据/保证；不直接生整页图 |
| 生图 | Nano Banana 优先，ChatGPT Images 备选，Ideogram 只做文字徽章 | 产品图 + 参考图 + 身份锁表 + 资产清单 | 分开的视觉资产，每张带验图自查 | 不生整页带文字的图；不渲染价格/数字；不编品牌名 |
| 建站 | Codex / Antigravity | 生好的图 + 真相表 + 文案 brief + 验收表 B | HTML/Shopify 页面，文字/价格/图标/尺寸全部代码化 | 不把图里的文字当事实抄；不改真相表；不自己验收 |
| 验收 | 独立一轮（换 agent 或换角色） | 参考图 + 真相表 + 验收表 A/B | 逐项打勾报告，不过项指明回哪一步 | 不凭“像不像”打分；不编造提升数字 |

## 待办
- 用一个新产品走一遍 1–6 步全流程，验证 v0.4 是否真的能落地，再定版成正式 skill（等 Bill 定产品）。
- 第十批：起点 2026-09-16 “Your buying box should do more than close the sale. It should help increase CR + AOV.”那条，再往下是同日“Your buying box shouldn’t just look good. It should help shoppers buy.”那条；Bill 2026-11-27 已定 225 条够蒸馏，第十批起只补新模板，不再逐批全并，抓不抓等 Bill 一句话。
- 正式 skill 已建成：`~/workspace/custom-skills/william-dtc-landing-page/SKILL.md`（内容与本稿 v0.4 一致，参考图精选 27 张在 `assets/reference/`，全量 201 张在 `~/workspace/william-dtc2y/batch-*/images/`）。

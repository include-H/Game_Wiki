# Windows Phone 时代 Wiki

> 说明：本文为面向中文读者整理的“Windows Phone 时代”平台史 / 时代史 Wiki。本文所说的“Windows Phone 时代”，并不只狭义指 2010 年后的 `Windows Phone 7 / 7.5 / 8 / 8.1 / Windows 10 Mobile`，也会适当前置到 `Windows CE`、`Pocket PC` 与 `Windows Mobile`，用来说明微软为何会进入手机平台竞争、它最初想把“手机上的 Windows”做成什么、后来又为何必须把旧路线推倒重来。本文主要参考 Microsoft News / Microsoft Blog / Windows Developer Blog / Microsoft Learn 生命周期资料、Nokia 公开资料、微软与诺基亚合作和收购公告、开发者资料、主流历史报道与公开 Wiki 整理而成。本文不把它写成参数表，也不把它写成 Lumia 购机指南，而是试图回答一个更重要的问题：为什么 Windows Phone 明明长期被认为“系统很漂亮、体验很顺、设计很先进”，最后却还是输掉了整个智能手机时代。

:::epigraph
它不是那种“什么都没做对”的失败平台。  
恰恰相反，它做对了太多后来被反复证明有价值的事情。  
Live Tiles、Metro、内容优先、手机上的 Xbox Live、  
手机像个人入口而不是图标抽屉、  
这些判断都不轻。  
可它输掉的，正是那个时代最不能输的一件事：  
在应用、开发者与市场规模形成正循环之前，  
它已经没有时间了。  
:::

---

## 1. 时代概览

如果说 `Windows Mobile` 代表的是微软把 PC 时代的延长线带到口袋里，那么 `Windows Phone` 代表的，就是微软在 iPhone 之后承认旧时代已经结束，并试图用一次几乎彻底重写的方式，重新定义“微软的手机应该是什么”。

这两个阶段表面上都带着 `Windows` 的名字，甚至都出自微软移动平台路线，但它们本质上不是同一类产品。

`Windows Mobile` 的根子在 `Windows CE`。它诞生于 PDA、手写笔、企业邮件、移动办公还很重要的年代，逻辑是“把桌面世界的重要能力缩小到手里”：文件、Office、Outlook、同步、企业接入、OEM 大量定制、多种形态设备并存。它像一台能打电话的迷你电脑，也像一套卖给运营商、厂商和企业客户的可裁剪平台。  
`Windows Phone` 则是 iPhone 之后的产物。它默认用户首先需要的不是“口袋里的小电脑”，而是一台围绕人、信息流、社交、媒体与触控体验组织起来的现代智能手机。它不再鼓励 OEM 无限定制，不再把桌面式 UI 缩小到手机里，也不再把 stylus、层层菜单和文件视图当成体验中心。它是一场明确的路线断代。

所以，Windows Phone 的故事，从来不是单纯的“微软手机失败史”。它其实分成三层：

1. `Windows CE / Windows Mobile` 时代，微软很早就理解手机和移动计算的重要性，但理解方式仍然带着明显的 PC 思维。
2. `Windows Phone 7` 开始，微软又很早意识到旧思路已经不行，于是做出一套设计史影响远大于市场成绩的新手机系统。
3. 到 `Windows Phone 8 / 8.1 / Windows 10 Mobile`，微软试图把手机重新接回“一个 Windows”的宏大路线，用 `NT 内核`、`通用应用`、`Continuum`、`UWP`、`One Windows` 去追赶，但这时 iPhone 与 Android 已经把平台战争的基本盘拿走了。

也正因为如此，Windows Phone 成了游戏史和平台史里一个极有代表性的对象：  
它不是没有魅力，反而魅力极强；  
不是没有设计野心，反而野心极大；  
不是没有技术方向，反而经常比别人更早看到一些方向。  
但平台战争从来不只看设计，也不只看单机体验。平台最终拼的是用户规模、开发者回报、应用供给、厂商联盟、运营商关系、升级路线、战略耐心，以及“你能不能在正确的年份做对正确的事”。

Windows Phone 最终没能做到这一点。

---

## 2. 引言

为什么微软一定要进入手机竞争？

因为对微软来说，手机从来不只是手机。  
它是下一个个人计算入口，是 `Windows` 之外的新终端，是 Office、搜索、地图、账号、云、游戏服务、广告体系和开发者平台的下一块落点。  
如果 PC 是 1990 年代和 2000 年代前半段的个人计算中心，那么 2000 年代后半段开始，微软已经不可能不问自己：  
当用户最常打开的屏幕不再是桌面，而是手里的那块小屏幕时，微软还剩下多少存在感？

这就是 Windows Phone 时代真正的背景。

所以它的失败，也不只是“一个手机系统没做起来”。  
它意味着微软在智能手机这个决定下一个十年数字入口归属的战场上，最终没有守住自己的平台位置。  
而它的历史地位之所以又始终不低，是因为它留下的并不是一堆过时参数，而是一整套仍然会被后人回望的设计遗产、产品判断和平台教训。

---

## 3. 时间线

### 3.1 1996：Windows CE 发布，微软正式把“Windows 进入移动设备”写成战略方向

`1996 年 9 月 16 日`，微软正式发布 `Windows CE`。官方当时就把它定义为一个面向“通信、娱乐、移动计算设备”的可扩展平台，目标不是桌面 PC，而是更广泛的非 PC 设备。  
这一步非常关键，因为它说明微软对移动计算的兴趣其实极早，并不是 iPhone 出来之后才临时起意。它从 1990 年代中后期就已经在想：Windows 不能只活在桌面。

但这里也埋下了后来的结构性问题：  
微软进入移动领域的时间很早，可它进入时所处的时代，仍然是 `PDA / Handheld PC / 移动办公终端` 的时代，而不是后来那种“以应用商店、触控交互、社交媒体、移动互联网内容分发为中心”的智能手机时代。

### 3.2 2000-2003：Pocket PC 与 Smartphone 路线成形，Windows Mobile 扎根企业和 PDA 传统

从 `Pocket PC 2000` 到 `Pocket PC 2002`，再到后来统一品牌的 `Windows Mobile 2003`，微软逐步把基于 `Windows CE` 的 PDA 与手机路线收束成一个更完整的移动平台家族。  
这一阶段的设备形态非常多：有手写笔大屏 PDA，有类似 BlackBerry 的键盘机，也有越来越像“能上网、能装软件的手机”的设备。

这代平台的典型气质很鲜明：

- 强调与 Windows PC 同步
- 强调 Outlook、Office、Exchange、企业移动办公
- OEM 和运营商可以深度定制
- UI 更像缩小版桌面，而不是专门为手指和内容流重新设计
- 软件分发并未形成后来 App Store 那种单一入口

它在当时并不算错误，甚至一度很有市场。很多早期智能手机、PDA 和企业移动终端都在这条路线上。问题在于，等到 iPhone 和 Android 重新定义智能手机之后，这条路会显得越来越旧。

### 3.3 2005-2009：Windows Mobile 5 / 6 / 6.5 延续旧逻辑，微软开始显出转身迟缓

进入 `Windows Mobile 5.0`、`6.0`、`6.1`、`6.5` 时代后，微软仍在持续更新移动平台。`2009 年`，微软还在为 `Windows Mobile 6.5` 推 `Marketplace for Mobile` 与 `My Phone`，试图补齐应用商店和云同步这一代智能手机平台越来越关键的基础设施。

但这时问题已经很明显了。

`iPhone` 在 2007 年重新定义了智能手机的人机界面，`App Store` 在 2008 年把“手机平台”明确变成“系统 + 商店 + 开发者生态 + 应用分发”的完整体系，`Android` 则在开放授权和多厂商合作中迅速铺开。  
相较之下，`Windows Mobile 6.5` 更像对旧平台的大修补，而不是对新时代的正面回答。它有浏览器改良、有新首页、有商店，但底层产品哲学还是旧的。

这也是微软后来必须重启的根本原因：  
它不是没看见手机，而是太久都在用上一代移动设备的逻辑理解手机。

### 3.4 2010：Windows Phone 7 Series 公布，微软承认旧路不够用了

`2010 年 2 月 15 日`，微软在 MWC 正式发布 `Windows Phone 7 Series`。这几乎可以视作微软移动平台史上最重要的断点之一。

官方在发布时已经把方向讲得很明白：  
它是“下一代 Windows Phone”，会带来全新的设计系统、`Live Tiles`、`Hubs`，并首次把 `Xbox LIVE` 与 `Zune` 体验带到手机上。  
这里的信号非常清楚：微软不打算继续修修补补 `Windows Mobile`，而是决定直接换一套面向现代智能手机的叙事。

这一代最大的意义，不在于“微软终于出了新手机系统”，而在于：

- 它是微软对 iPhone 时代的正式回答
- 它彻底放弃了 Windows Mobile 的老式产品气质
- 它把设计和体验提到了比“兼容旧桌面习惯”更高的位置
- 它试图把微软内部的 `Office / Xbox / Bing / Zune / Windows Live` 整合为一个手机平台人格

也正是在这里，`Metro`、`Panorama`、`Pivot`、`Live Tiles`、`People Hub` 等后来影响极大的元素，第一次真正被系统化推出。

### 3.5 2010-2011：Windows Phone 7 上市，系统获得好评，但基础功能和生态仍然偏弱

`2010 年 10 月`，微软与合作伙伴公布首批 Windows Phone 7 机型，`2010 年 11 月 8 日`正式在美国开售。  
这代系统的媒体印象很鲜明：界面不跟风，动效漂亮，排版极强，信息结构清楚，跟当时大量图标宫格、拟物化或半桌面式手机相比，辨识度极高。

但问题也很快暴露：

- 初代功能并不完整，缺少很多用户已经默认应该存在的能力
- 微软为了统一体验，限制硬件与定制，反而降低了厂商和运营商的“发挥空间”
- 市场起步太晚，iPhone 和 Android 已经先建立了心智
- 开发者还在观望，应用供给明显不足

Windows Phone 7 的评价因此从一开始就很矛盾：  
“这是个很漂亮的系统”，和“它还不够成熟，也没有足够多应用”，几乎总是同时出现。

### 3.6 2011：Mango 到来，Windows Phone 7.5 进入相对完整阶段；诺基亚与微软结盟

`2011 年 5 月`，微软发布代号 `Mango` 的下一版 Windows Phone，后来正式作为 `Windows Phone 7.5` 推出。官方称其带来数百项更新，包括更完整的多任务、IE9、更多社交整合、更成熟的消息能力与更广的语言支持。  
从产品完成度来说，`Mango` 才是很多人心里“Windows Phone 真正成熟起来”的起点。

但这一年的真正历史大事，是 `2011 年 2 月 11 日` 微软与诺基亚宣布广泛战略合作。  
诺基亚决定以 `Windows Phone` 作为其主要智能手机战略，双方宣称要共同建立“第三个全球移动生态”。

这件事的历史分量极大。

因为当时的诺基亚虽然已经显出衰势，但仍然是全球手机行业最有渠道、制造、品牌、运营商关系和国际分发能力的公司之一；而微软缺的恰恰就是手机硬件、供应链、运营商覆盖和全球终端执行力。  
从纸面上看，这几乎是最合理的联盟：  
微软给系统、服务、开发工具、Office、Xbox、Bing；  
诺基亚给工业设计、硬件、影像、地图、渠道、全球覆盖。

这也是为什么当年很多人真的相信，Windows Phone 或许能成为 iOS 与 Android 之外的“第三极”。

### 3.7 2011-2013：Lumia 出现，Windows Phone 的品牌形象与硬件魅力在诺基亚手里达到高点

Lumia 系列很快成了 Windows Phone 的真正面孔。  
如果说 HTC、三星等伙伴给了 Windows Phone 最初的硬件落地，那么真正把 Windows Phone 的视觉辨识度、工业设计和大众记忆做出来的，几乎就是诺基亚。

`Lumia 800`、`Lumia 900`、后来的 `Lumia 920`、`Lumia 1020` 等机型，让 Windows Phone 的“看起来就不一样”变成了现实：

- 大胆的聚碳酸酯彩色机身
- 一体化工业设计
- 与 Metro 风格高度一致的外观语言
- PureView、蔡司镜头、夜景和影像卖点
- Nokia Maps / Drive 等差异化服务

到这个阶段，Windows Phone 的矛盾更加鲜明了：  
它在“设备是否有魅力”这个问题上，经常答得很好；  
但它在“平台是否有生态”这个问题上，答得越来越吃力。

### 3.8 2012：Windows Phone 8 改用与 Windows 8 共享核心技术，平台开始重新接回“大 Windows 路线”

`2012 年 6 月 20 日`，微软宣布 `Windows Phone 8`。官方明确强调，这一代将基于与 `Windows 8` 相同的核心技术。  
这意味着一个非常关键的变化：

`Windows Phone 7` 仍然立足于 Windows CE 传统；  
`Windows Phone 8` 则开始转入与桌面 Windows 更接近的 `NT` 技术路线。

这是技术层面的重大升级，但同时也制造了巨大的历史代价：  
早期 `Windows Phone 7.x` 设备无法完整升级到 `Windows Phone 8`，只能得到 `Windows Phone 7.8` 这种带有部分新界面的安慰式更新。

对用户和开发者来说，这是一记很重的打击。  
因为它等于公开承认：  
平台虽然在前进，但前一代刚买不久的用户已经站在旧线了。

平台战争里，升级断裂是极危险的。  
它会让用户担心“现在买会不会马上被抛下”，也会让开发者担心“我要押注的到底是哪一代平台”。

### 3.9 2013-2014：Windows Phone 市场份额短暂增长，成为“全球第三”，但第三的位置并不稳

到 `2013 年` 前后，Windows Phone 的全球份额有过一段相对亮眼的增长期。IDC 数据一度把它列为全球第三大智能手机系统，微软官方与市场报道也都曾反复强调它是增长最快的平台之一。  
这段时期的增长并非虚假，尤其在部分欧洲市场、部分新兴市场，以及诺基亚推动下的中低端机型上，Windows Phone 确实取得过存在感。

但这段增长的性质很值得说明：

- 它更多是“第三名增长”，不是对前两名构成真正威胁
- 规模仍远低于 iOS 与 Android
- 增长高度依赖诺基亚 Lumia
- 非诺基亚 OEM 在 Windows Phone 上的存在感越来越弱
- 应用生态仍未真正反转

也就是说，它在统计意义上成为了“第三”，却始终没有形成真正稳定的第三生态。

### 3.10 2014：Windows Phone 8.1 让系统更成熟，但也更像在补课

`2014 年`，微软推出 `Windows Phone 8.1`，加入 `Cortana`、`Action Center`、更成熟的通知与输入体验、更多细节完善。  
这一版通常被视作 Windows Phone 体验最成熟的阶段之一。

但它也暴露出一个现实：  
很多功能其实是平台在向 iOS 和 Android 长期已经存在的基础能力补课。  
换句话说，Windows Phone 一方面仍然保留了自己非常强的设计人格；另一方面又不得不承认，市场已经给智能手机定义了一套“没有就不行”的基础清单。

因此，`8.1` 是一版完成度很高的更新，但它更像一个“终于补齐很多该有东西”的时刻，而不是一个足以扭转平台命运的时刻。

### 3.11 2013-2014：微软收购诺基亚手机业务，Lumia 从“微软合作伙伴的明星产品”变成“微软自己的手机业务”

`2013 年 9 月 3 日`，微软宣布将收购诺基亚 `Devices & Services` 业务；`2014 年 4 月 25 日` 交易完成。  
这件事在当时被视作微软要对手机业务“all in”的标志。

它的历史意义有三层：

第一，微软承认仅靠授权模式已经不够。  
如果 Windows Phone 想活下去，微软必须直接掌握硬件执行力、供应链、工业设计和手机品牌运作。

第二，它让 Lumia 从“合作样板机”变成“微软手机战略本体”。  
这提升了控制力，也减少了平台中立性。Windows Phone 更像微软自己的业务，而不再像一个有很多厂商共同参与的开放阵营。

第三，它暴露了平台困局已经严重到要用并购来硬解。  
一个真正健康的手机生态，不应长期只靠单一 OEM 撑住；微软最后却不得不把最关键的 OEM 直接买下来，这本身就说明生态层已经不稳了。

### 3.12 2015：Windows 10、UWP、Continuum 登场，微软试图用“一个 Windows”重写移动意义

到了 `Windows 10` 时代，微软的移动战略出现了进一步转向。  
它不再只是想做“一个第三名手机系统”，而是想把手机纳入“一个统一 Windows 平台”的大图景。

`2015 年 Build`，微软大谈 `Universal Windows Platform`。  
`2015 年` 下半年，首批预装 `Windows 10` 的 Lumia 950 / 950 XL 上市，主打 `Continuum for Phones`，即手机接上显示器、键鼠与扩展坞后，以近似 PC 的方式运行通用 Windows 应用。

这是 Windows Phone 时代最有未来感、也最像“微软式想象力”的阶段。  
它的潜台词其实很大胆：

- 如果手机已经是人人随身携带的主设备，那么它为什么不能就是你的 PC？
- 如果 Windows 能统一 PC、平板、手机、Xbox、IoT，那么开发者为什么不为“整个 Windows 世界”写应用？
- 如果 UWP 成立，那么手机就不必单独和 iOS / Android 比单点应用数量，它可以借“大 Windows”反过来获得规模。

这是个很有逻辑的设想。  
但它出现得太晚，也太依赖一个前提：  
开发者必须先相信“Windows 手机仍值得下注”。

而现实是，那时很多开发者已经不相信了。

### 3.13 2015-2017：微软对手机业务大规模重组，Windows Phone 事实上开始退出主流竞争

`2015 年 7 月`，微软宣布重组手机硬件业务，并确认高额减值与大规模裁员。  
这基本意味着微软已经承认：收购诺基亚手机业务并没有按原计划把 Windows Phone 推上更高台阶。

后面的故事就逐渐转向收缩：

- 手机新品越来越少
- 市场宣传重心持续下降
- 第三方应用继续流失或不更新
- 微软自己也越来越少把手机当成面向大众的核心业务来讲

`Windows 10 Mobile` 之后，平台名义上仍在更新，但事实上已经不再是主流竞争者。

### 3.14 2019：Windows 10 Mobile 支持结束，一个时代正式终章

微软后来明确说明，`Windows 10 Mobile version 1709` 是最后一版 Windows 10 Mobile，`2019 年 12 月 10 日` 结束支持。  
到这里，Windows Phone / Windows Mobile 作为微软主流手机系统的历史，才算真正画上句号。

它的退场并不突然。  
真正决定胜负的时刻，其实更早，在生态已经注定无法反转的时候就发生了。  
2019 年只是官方把最后一页翻完。

---

## 4. 基础信息速览

### 4.1 平台速览

| 维度 | 信息 |
|------|------|
| 平台主题 | Windows Mobile / Windows Phone / Windows 10 Mobile |
| 历史根系 | Windows CE |
| 主要时代跨度 | 约 1996-2019 |
| 移动平台断代节点 | 2010 年 `Windows Phone 7 Series` 公布 |
| 关键合作方 | Nokia、HTC、Samsung、LG、Huawei 等 |
| 关键品牌 | Pocket PC、Windows Mobile、Windows Phone、Lumia |
| 关键设计符号 | Metro / Modern UI、Live Tiles、Hub、Panorama、Pivot |
| 关键生态卖点 | Office、Outlook、Bing、Xbox LIVE、People Hub、Cortana |
| 后期关键设想 | NT 核心统一、UWP、Continuum、One Windows |
| 正式退场节点 | Windows 10 Mobile 支持于 2019 年 12 月 10 日结束 |

### 4.2 关键词

- Windows CE
- Pocket PC
- Windows Mobile
- Windows Phone 7
- Mango
- Metro / Modern UI
- Live Tiles
- Lumia
- Nokia
- Windows Phone 8
- Windows Phone 8.1
- Cortana
- Windows 10 Mobile
- UWP
- Continuum
- App Gap
- Xbox LIVE

### 4.3 历史定位速写

| 维度 | 关键词 |
|------|--------|
| 设计史印象 | 最有辨识度的现代手机 UI 之一 |
| 市场印象 | 系统好评、生态失利 |
| 技术印象 | 从 CE 到 NT、从独立手机系统到 One Windows |
| 硬件印象 | Lumia 时代的工业设计高光 |
| 游戏印象 | 手机上的 Xbox LIVE 尝试者 |
| 历史评价 | 历史地位明显高于最终市场结果 |

---

## 5. 技术与平台设计

### 5.1 为什么微软会进入手机平台竞争

这个问题表面上很简单，答案却不能只写成“因为手机市场很大”。

微软进入手机平台竞争，最根本的原因是：  
它太早就知道，下一代个人计算不会只发生在桌面上。

从 `Windows CE` 时期开始，微软就一直想让 Windows 从 PC 扩展到更多设备；到了 `Windows Mobile 6.5` 时，它又在反复强调“PC、Web、Phone 的连接”；到 `Windows Phone 7` 发布时，它更直接把 `Xbox LIVE`、`Office`、`Bing`、`Zune` 等微软内部资源带到手机上。

这说明对微软来说，手机平台至少有四层意义：

1. 个人计算入口之争。  
如果手机成为用户最常用的计算设备，微软不能完全缺席。

2. 服务入口之争。  
Office、邮件、搜索、地图、媒体、云存储、社交连接，都需要手机端落脚点。

3. 开发者平台之争。  
谁掌握主流终端，谁就更容易掌握开发者时间和应用分发入口。

4. Windows 外延之争。  
微软长期的思维不是“做一部手机”，而是“让 Windows 成为跨设备平台”。

也因此，微软进入手机市场不是偶然，而是必然。  
它真正的问题不是“为什么进来”，而是“它进入得虽早，却没能在正确的代际用正确的方法完成转身”。

### 5.2 Windows Mobile 与 Windows Phone 本质上有什么不同

很多后来回看这段历史的人，会把两者都叫成“微软手机系统”。  
但从产品哲学看，它们几乎属于两个时代。

`Windows Mobile` 的核心是“移动计算设备”。  
它延续的是 PDA、企业终端、可同步的小型 Windows 设备逻辑。它更像一套可授权、可定制、可接入企业 IT 体系的迷你计算平台。

`Windows Phone` 的核心则是“现代智能手机”。  
它把人与信息放在交互中心，默认用户要的是快速读取、即时沟通、社交关系、媒体消费和服务聚合，而不是文件树、层级菜单和桌面缩影。

两者至少有五个本质差异：

1. 交互哲学不同。  
Windows Mobile 偏 stylus 和菜单式；Windows Phone 完全围绕触控、文字、动效和内容流重新设计。

2. 平台控制方式不同。  
Windows Mobile 更像 OEM 平台；Windows Phone 强调统一规范、统一硬件按钮、统一体验。

3. 用户心智不同。  
Windows Mobile 面向“我想把电脑能力带在身上”；Windows Phone 面向“我想要一台真正现代、个人化的手机”。

4. 生态组织方式不同。  
Windows Mobile 时代的软件世界更分散；Windows Phone 时代的基础逻辑是应用商店、认证、统一分发。

5. 时代竞争对象不同。  
Windows Mobile 主要面对的是 Symbian、Palm、BlackBerry 及早期智能终端；Windows Phone 正面对抗的是 iPhone 和 Android。

所以，Windows Phone 不是 Windows Mobile 7。  
它本质上是微软在手机平台上的一次“自我否定之后的重启”。

### 5.3 Metro / Live Tiles / Modern UI 为什么在设计史上影响很大

Windows Phone 在设计史上的地位，很大程度上就来自 `Metro`。

官方和开发者资料里，微软把 Metro 反复概括为几条核心原则：  
强调排版、强调内容先于装饰、强调留白、强调动效、强调“content over chrome”。  
这在 2010 年前后的手机行业里非常特别。

因为那时主流智能手机 UI 主要有两种大方向：

- 一种是拟物化和图标宫格，把 app icon 作为首页主角；
- 另一种是带强烈桌面遗风的小组件、列表和菜单系统。

而 Windows Phone 给出的是第三种答案：

- 首页不是静态图标墙，而是会更新的 `Live Tiles`
- 重点不是“把应用摆给你看”，而是“把信息直接推到你面前”
- 大字号、强排版、横向 Panorama 和 Pivot 强调的是阅读流与信息分组
- UI 装饰被压到很低，内容本身成为视觉主角
- 动效不是花哨附属，而是信息层级和空间感的一部分

它影响大，首先是因为它太有辨识度。  
你哪怕只看一眼 Lumia 首页，也知道那不是 iPhone，不是 Android，也不是 BlackBerry。

它影响大，更因为它提出了一种后来被广泛验证的判断：  
在移动时代，首页不一定非得是“启动器”，它也可以是“信息看板”；  
界面不一定靠图标和拟物来建立亲和力，排版、节奏与运动也可以；  
系统可以更像一块有生命感的信息面板，而不是一个等待你逐层点开的应用仓库。

后来 Android 小组件、信息卡片、动态内容入口、通知中心、材质化与扁平化的普及，都不能简单说是直接来自 Windows Phone；但 Windows Phone 确实是这场设计转向里最早、最完整、也最系统化的代表之一。

这也是为什么它经常被看作“设计史地位高于商业结果”的典型平台。  
它未必赢了市场，但它明显留下了风格遗产。

### 5.4 Live Tiles 为什么迷人，又为什么最后没成为胜负手

`Live Tiles` 是 Windows Phone 最著名的符号，也是它最典型的矛盾之一。

它迷人的地方很直接：

- 让用户不进 app 也能看到更新
- 让首页像一张会呼吸的个人信息板
- 把“联系人、天气、相册、日程、消息、音乐”都做成可 glance 的入口
- 与 Metro 的强排版和颜色体系配合后，形成极强的系统人格

在那个很多手机首页都只是 app 图标陈列的年代，Live Tiles 的确让 Windows Phone 看起来更“活”。

但它没成为胜负手，也有很现实的原因：

1. 它解决的是“看起来更先进”和“信息更可 glance”的问题，不是“有没有你必须用的 app”的问题。  
平台战争里，这两类问题权重并不相同。

2. 它高度依赖开发者适配。  
没有足够多高质量应用认真做 Tile，系统设计优势就会打折。

3. 很多用户会称赞它“好看、好用”，却未必会因为它放弃已有社交关系链和应用资产去换平台。

也就是说，Live Tiles 是非常强的体验创新，但不是足以单独扭转生态差距的核按钮。

### 5.5 Windows Phone 8 的真正意义：它不是一次普通升级，而是一次底层换轨

很多人记得 `Windows Phone 8`，主要记得它带来更好的硬件支持、更高分辨率、多核、NFC 等。  
但它真正的大事，其实是微软把手机平台从 `CE` 传统切到与 `Windows 8` 更统一的核心技术路线。

这一步的重要性在于：

- 它让手机和大 Windows 世界更接近
- 它让微软后面讲“统一平台”有了底层依据
- 它让开发工具、内核能力、安全模型与设备支持出现新的可能

但这一步的代价同样很重：  
`Windows Phone 7.x` 与 `8` 之间被切出一道用户能真切感受到的代差。

从纯技术角度看，这可能是必要升级；  
从平台经营角度看，这却很伤。  
因为一个新兴平台最怕的，就是用户刚买、开发者刚跟、结果路线马上变。

### 5.6 Windows 10 Mobile、UWP 与 Continuum：微软后期设想为什么那么“微软”

如果说 Windows Phone 7 的气质是“设计革命”，  
那么 Windows 10 Mobile 的气质就是“平台大一统”。

`UWP` 的理想很典型：  
开发一次，跨 `PC / Phone / Xbox / HoloLens / IoT` 运行；  
Windows 10 共享统一内核与统一商店；  
手机不再是孤岛，而是“Windows 家族的一员”。

`Continuum` 则把这个理想具象化了。  
它不是单纯投屏，而是让支持的 Windows 手机接上大屏、键盘和鼠标之后，以接近桌面工作的方式运行通用应用。  
这套设计本身极有魅力，因为它直击微软最擅长的“生产力”叙事：  
手机不只是消费终端，它还能延伸成工作终端。

这套设想非常“微软”，因为它不只是想赢手机市场，而是想重写“手机是什么”。

问题在于，市场并不会因为你的愿景更高远就自动给你第二次机会。  
当时多数用户首先关心的是：

- 微信、Instagram、YouTube、Google 服务、银行 app、打车 app、视频 app 完不完整
- 朋友是不是也在这个平台
- 常用软件是不是官方而且更新及时
- 买了之后会不会很快被放弃

而 UWP 与 Continuum 解答的是另外一类问题：  
“如果 Windows 跨设备统一，未来会不会形成规模优势？”  
这问题在理论上成立，在 2015 年的现实里却太晚了。

---

## 6. 软件 / 应用 / 游戏生态

### 6.1 为什么开发者生态始终没做起来

这是 Windows Phone 历史里最关键的问题。

很多人会简单说“因为应用少”。  
但真正的问题不是结果，而是为什么应用总补不齐。

原因至少有六层：

1. 起步太晚。  
当 Windows Phone 7 在 `2010 年`登场时，iPhone 已经完成第一轮定义，Android 也已进入高速扩张期。开发者最宝贵的不是钱，而是时间和优先级。Windows Phone 进入时，别人已经先拿走了优先级。

2. 用户规模始终不足。  
开发者最终看的是投入产出比。平台用户量不够、付费规模不够、广告变现不够，很多公司就不会把 Windows Phone 列为首发甚至同步开发对象。

3. 路线切换频繁，信心受损。  
Windows Mobile 到 Windows Phone 7 是一次断代；  
Windows Phone 7.x 到 8 又是一次断层；  
8.1 到 Windows 10 Mobile 则继续把平台叙事推向“统一 Windows”。  
每一次都会让开发者重新判断：这条线到底稳不稳。

4. 第三方厂商支持逐步塌缩。  
真正撑住 Windows Phone 的硬件几乎只剩诺基亚 / Lumia。生态一旦过度依赖单厂商，就很难给开发者传递“这是一个长远、多元、稳定的平台市场”。

5. 核心应用的缺失是滚雪球式的。  
没有头部 app，用户不来；  
用户不来，开发者不来；  
开发者不来，头部 app 更不来。  
这就是平台战争里最典型的负循环。

6. 微软自己也没能形成足够强的生态硬拉力。  
它确实投入过大量补贴、合作和拉拢，也确实把 Office、Outlook、Xbox Live、Bing、OneDrive 等资源整合进来，但这些都没能替代大众真正每天要用的外部应用。

所以，Windows Phone 的开发者生态不是“从来没人支持过”，而是“始终没有跨过自发繁荣的临界点”。

### 6.2 为什么会出现“系统体验被称赞，但应用生态失败”的矛盾

这是 Windows Phone 最经典的悖论。

一边是很多用户和媒体长期认可它：

- 界面漂亮
- 动画流畅
- 交互统一
- 系统不卡
- 拍照机型有亮点
- 信息组织比很多同时代 Android 机更清爽

另一边则是它始终打不过生态。

这矛盾的本质在于：  
“系统体验”解决的是你在一台手机上如何使用已有能力；  
“应用生态”决定的是这台手机到底是不是完整生活入口。

如果平台缺的是美感、流畅度、统一性，系统优秀能弥补。  
但如果平台缺的是用户真正离不开的服务网络、社交关系链、内容入口与支付场景，系统优秀就很难补。

Windows Phone 长期处在一种很尴尬的位置：

- 它让已经买到的人觉得顺手
- 却不够让没买的人愿意迁移

这就是为什么它的口碑经常高于销量，系统好评也经常无法转化成生态胜利。

### 6.3 “App Gap” 到底意味着什么

Windows Phone 的 “app gap” 从来不只是“总数比别人少”。

真正致命的是三种缺口同时存在：

1. 头部应用缺口。  
用户真正天天要用的平台型应用缺席、来得晚、功能残缺，或者长期只有第三方替代品。

2. 更新节奏缺口。  
哪怕有官方应用，也经常慢于 iOS 和 Android，版本同步性不足，功能完整度不一致。

3. 心理预期缺口。  
当大众形成“这平台 app 可能没有、即使有也可能不是官方”的集体印象后，平台的劣势会远大于真实数量差距。

平台战争里，后两者往往比第一者更可怕。  
因为一旦用户和开发者都默认你是“可能缺东西的平台”，你就会在选择那一刻先输一半。

### 6.4 手机上的 Xbox / Xbox LIVE / 成就体系延伸：Windows Phone 在游戏生态上的独特位置

Windows Phone 在游戏史上的特殊价值，很大一部分来自 `Xbox LIVE`。

微软在 `Windows Phone 7` 发布时，就明确把 `Xbox LIVE` 作为核心卖点之一。  
手机上的 `Games Hub` 能让玩家看到头像、成就、GamerScore、好友关系和排行榜。  
这件事在当时非常有意思，因为它意味着微软不是把手机游戏只当成“消磨时间的小应用”，而是试图把它接进 Xbox 的统一玩家身份体系。

这套设想在游戏史上很重要，因为它延续了微软从 `Games for Windows — LIVE` 到 Xbox 360 时代一直在做的一件事：  
统一账号、统一成就、统一社交层。

放到 2010 年前后看，Windows Phone 的这一步其实很超前。  
它想让手机游戏不再只是孤立的“本地小游戏”，而是完整在线玩家身份的一部分。

这也让 Windows Phone 的游戏生态，从一开始就和一般手机平台不完全一样。  
它有更明显的主机平台影子，也更强调：

- Xbox 品牌背书
- 成就与 Gamerscore
- 排行榜与好友网络
- 官方精选的 Xbox LIVE 游戏阵容

### 6.5 Windows Phone 上的手游生态与代表作品

Windows Phone 的手游生态从来不是荒漠，但它也始终没变成主流市场。

早期比较有代表性的类型与作品，大致包括：

- 由微软重点推动的 `Xbox LIVE` 手机游戏
- EA、Gameloft、Rovio 等较大厂商带来的移植或定制作品
- 典型时代手游，如《Angry Birds》《Fruit Ninja》《Jetpack Joyride》《Cut the Rope》《Plants vs. Zombies》这一类
- 微软第一方或强绑定 Xbox 品牌的作品，如《Halo: Spartan Assault》《Halo: Spartan Strike》
- 一批适合触屏与短时游玩的益智、休闲、街机类作品

这些游戏说明了一件事：  
Windows Phone 从来不是“完全没有游戏可玩”。  
相反，它在某些年份甚至挺有一种“精选小而美游戏库 + Xbox 气质加成”的味道。

但它的游戏生态一直有明显边界：

- 大量爆款来得晚
- 并非所有热门手游都会同步上
- 版本更新经常滞后
- 一些服务类、社交强绑定类游戏天然更倾向 iOS / Android
- 真正支撑手游时代的免费游玩、广告变现、社交传播、渠道投放体系并未在 Windows Phone 上形成主流

所以 Windows Phone 的手游生态更像“有亮点、有精品、有少量代表作”，而不是“主流手游大盘的一部分”。

### 6.6 为什么它没能形成像 iOS / Android 那样的手游主流市场

这背后有几个决定性因素：

1. 用户盘子不够大。  
手游厂商首先要看装机量和活跃用户。没有规模，就没有首发优先级。

2. 免费游戏时代的商业模式不站在它这边。  
手游主流市场很快进入 F2P、广告、社交裂变、持续运营、频繁更新的竞争逻辑。Windows Phone 在这套体系里没有成为最优投放平台。

3. 发行侧动力不足。  
很多厂商会优先做 iOS，再做 Android；能不能轮到 Windows Phone，要看平台补贴、移植成本和市场预期。

4. 社交平台与支付生态弱势。  
手游并不只靠“游戏能跑”，还要靠账号、支付、社交分享、消息推送、广告工具、数据分析等一整套外围基础设施。

5. 头部厂商长期观望。  
一旦头部手游公司普遍观望，中小开发者也很难把它当成必须进入的市场。

这导致 Windows Phone 在手游史上的位置很特殊：  
它不是没有参与过手机游戏时代，而是始终没能进入“决定时代走向的大盘”。

### 6.7 对独立开发者、移植和跨平台策略的影响

Windows Phone 对独立开发者并非完全没有吸引力。

相反，它在某些阶段其实对独立开发者相当友好：

- 微软愿意给曝光
- 商店竞争相对没那么拥挤
- 平台需要内容，独立团队更容易被看见
- Xbox LIVE 与 Windows 品牌加成让一部分作品更有“平台感”

但问题也很清楚：

- 曝光不等于销量
- 用户盘子不足会限制长期回报
- 跨平台开发时，Windows Phone 往往不是第一优先
- 后期再叠加 UWP 和统一 Windows 路线后，开发者确实看到了“多端共用代码”的希望，但希望始终没有完全兑现成市场

因此，Windows Phone 在独立开发者史上的意义，不在于它建立了庞大独立市场，而在于它让很多团队更早认真思考：

- 手机、PC、平板能否共用一套应用逻辑
- 成就系统和平台身份能否从主机延展到移动端
- 一个不在主流大盘里的平台，是否还能通过精选内容维持文化存在感

这些问题后来的确在更多平台上继续出现。

---

## 7. 为什么它会失败

### 7.1 第一层原因：它进入得并不晚，但它真正转身时已经晚了

这是 Windows Phone 历史里最容易被误解的地方。

微软不是一家“压根没看到手机趋势”的公司。  
它从 Windows CE 到 Windows Mobile，进入移动计算其实非常早。

它真正的问题是：  
它很早进场，却太久都在用上一代移动设备的思维理解这场战争。  
等它真正用 `Windows Phone 7` 去回答新时代时，iPhone 和 Android 已经分别拿走了“定义权”和“规模权”。

所以它输得不是“起跑太晚”，而是“真正换跑姿时已经太晚”。

### 7.2 第二层原因：平台重启太彻底，导致积累断裂；但不重启又不行

Windows Mobile 到 Windows Phone 7 的断代，在产品上几乎不可避免。  
旧系统确实已经不适合与 iPhone / Android 正面打。

但彻底断代的后果是：

- 旧用户资产和开发经验价值下降
- 平台需要重新招商、重新教育市场
- 用户会感知到“上一代微软手机不算数了”

到了 Windows Phone 8，再从 CE 传统切向 NT 路线，又再来一次裂痕。

这让 Windows Phone 一直有种“每次快站稳一点，又要重新讲一次自己是谁”的感觉。  
对一个新平台来说，这是很致命的。

### 7.3 第三层原因：开发者永远更看重规模，而不是只看设计

这是最残酷、也最根本的一条。

用户会因为设计喜欢你。  
媒体会因为创新夸你。  
但开发者最终要看回报。

只要 Windows Phone 用户规模不够大，平台就很难让头部互联网公司把它当成最高优先级。  
只要头部应用不上或不上完整版本，用户又更不会迁移。  
这就是平台战争的闭环。

微软当然试过很多办法：

- 资金激励
- 合作引入
- 强调开发工具
- 把 Windows 与 Windows Phone 讲成一个更大的机会

但它始终没跨过最核心的一步：  
让开发者相信“这里有足够多用户，而且这批用户会长期留下来”。

### 7.4 第四层原因：它的合作与收购都带来帮助，也带来路径依赖

诺基亚合作当然是 Windows Phone 史上最重要的正面力量。  
没有诺基亚，Windows Phone 的硬件魅力和市场存在感只会更弱。

但同样因为诺基亚太重要，Windows Phone 也越来越像“诺基亚 + 微软”的事，而不是整个手机行业都愿意参与的事。  
到最后微软直接把诺基亚手机业务买下来，控制力更强了，生态开放感反而更弱了。

平台如果长期只剩一个真正有号召力的硬件伙伴，实际上已经不太像健康生态，更像被单一血源续命。

### 7.5 第五层原因：它和 iPhone / Android 的竞争关系，一开始就不是公平追赶

Windows Phone 面对的不是一个空市场，而是两个性质完全不同、却都很强的对手。

`iPhone / iOS` 赢在：

- 先定义了现代智能手机体验
- 开发者优先级极高
- 高端用户与品牌心智牢固

`Android` 赢在：

- 多厂商快速铺货
- 各价位段覆盖能力极强
- 运营商、OEM、地区市场适配能力强
- 规模形成极快

Windows Phone 则卡在中间：

- 它没有 iPhone 那样的“第一定义权”
- 又没有 Android 那样的“开放规模化扩张能力”
- 它想走高一致性、高体验路线，但市场基本盘不足
- 它想靠诺基亚补规模，但又没补到 Android 那个量级

所以它很长时间都不是“第三个均势选手”，而是“设计上强势、规模上劣势”的追赶者。

### 7.6 第六层原因：Windows Phone 8 到 Windows 10 Mobile 的路线问题，太想借大 Windows 翻盘

这条路线不是完全错。  
从技术和战略完整性看，微软想把手机纳入“大 Windows 平台”是非常自然的。

问题在于，当时手机市场要的不是“一个更统一的 Windows 愿景”，而是“一个今天就不能缺主流应用的平台”。

UWP、统一商店、通用应用、Continuum，这些设想都有逻辑，但它们都建立在一个前提上：  
手机端还没死。

而现实是，手机端恰恰已经在失血。  
微软试图用未来平台结构来解决当前生态问题，但当前生态问题又在不断削弱别人相信这套未来结构的意愿。

这就是 Windows 10 Mobile 最痛的地方：  
它可能是逻辑上最完整的一代，  
却也是市场上最来不及的一代。

### 7.7 第七层原因：Continuum、UWP 等后期设想为何没能扭转局面

`Continuum` 很惊艳，`UWP` 很有野心，但它们最终都没有救活手机业务，原因大致有四个：

1. 它们主要吸引的是“愿景认同者”和一部分生产力场景用户，不足以打动大众换机。

2. 它们依赖开发者提供高质量通用应用，但开发者本来就因为手机份额太低而不愿投入。

3. “手机像 PC”这个命题本身很酷，但大多数用户并不会因为这个特性放弃已有 iOS / Android 生态。

4. 这套路线更像在重新发明“手机之后的计算”，而不是赢下当时那场已经打到中盘的智能手机市场份额战争。

也就是说，它们不是错误方向，而是来得太晚、落地土壤太薄。

### 7.8 微软想做的 UWP 为什么没做成，反而更像被苹果做成了

这其实是 Windows Phone / Windows 10 Mobile 后期历史里最值得写透的一层讽刺。

微软当年想通过 `UWP` 完成的，并不只是“让开发者少写几套代码”这么简单。  
它真正想做的是：

- 用统一应用模型把 `PC / Phone / Tablet / Xbox / 其他 Windows 设备` 接成一个平台家族
- 用统一商店、统一账号、统一购买和统一分发降低开发者进入门槛
- 让应用可以随着屏幕尺寸和输入方式变化而适配，而不是每个平台都重新做一套
- 让手机不再是孤立终端，而是 Windows 整体生态的一部分
- 让开发者不必单独为“一个份额偏小的手机系统”下注，而是为“整个 Windows 世界”下注

从逻辑上说，这套设想并不荒唐，甚至非常先进。  
它抓住的问题也是真问题：  
如果未来个人计算不再只发生在一种设备上，那么应用、账号、商店和用户资产当然会倾向跨设备统一。

问题在于，微软试图用 `UWP` 解决的，是一个已经被手机市场基本盘反过来卡死的问题。

`UWP` 需要开发者相信“Windows 手机仍然值得投入”，这样统一平台才有吸引力；  
但开发者之所以不相信，恰恰是因为 Windows 手机本身已经缺乏足够大的用户规模。  
于是就出现了一个非常典型的死结：

- 没有手机规模，开发者不愿意认真做 UWP
- 没有足够多高质量 UWP，手机端更难变得有吸引力
- 手机端不吸引人，“一个 Windows” 的统一叙事也就更难成立

微软的后期路线因此带着一种很典型的“平台公司思维”：  
它试图先把未来平台结构讲通，再让市场接受这套结构。

而苹果后来更像是把同类问题用另一种更务实的方式做成了。

苹果并不是按微软 `UWP` 的原样去做，但它确实在结果上，更像完成了微软当年的那种期待：

- `iPhone` 先赢下移动时代最核心的入口
- 再让 `iPad`、`Apple Watch`、`Apple TV`、`Mac` 逐步共享账号体系、购买关系、订阅、云同步和开发工具链
- 再通过 `SwiftUI`、`Mac Catalyst`、统一芯片架构、跨设备 API 与跨设备服务，把多端一体的体验慢慢落下来
- 更关键的是，苹果并不强求“同一个 app 原封不动跑遍所有设备”，而是接受“同生态、同工具链、同服务层、但按设备形态分别优化”这件事

也就是说，苹果做成的不是 `UWP` 的字面版本，而是更接近 `UWP 想解决的问题本身`：

- 用户资产跨设备延续
- 开发者工具链趋于统一
- 商店和账号体系统一
- 多设备共享一个生态，而不是彼此孤立

微软和苹果最大的差别在于顺序。

微软更像是：

1. 先讲“统一平台的未来”
2. 再希望开发者相信这套未来
3. 再希望手机端因此获救

苹果更像是：

1. 先赢下最关键的设备和用户规模
2. 再让开发者默认这个生态值得长期投入
3. 最后把跨设备统一这件事一步步做成自然结果

换句话说，微软输的并不只是 `UWP` 本身，而是它想在手机平台尚未站稳时，就提前收获统一生态的复利。  
苹果则是先把最重要的那棵树种活，再慢慢把“统一生态”长出来。

所以如果把这段历史说得更准确一点，那么更合适的判断不是“苹果把 UWP 做成了”，而是：

微软当年在 `UWP / One Windows / Continuum` 里想解决的那批跨设备平台问题，后来确实更多地被苹果用另一种更克制、更现实、也更不依赖单点翻盘的方式做成了。

---

## 8. 历史定位

### 8.1 诺基亚合作、Lumia 系列、收购 Nokia 手机业务的历史意义

Windows Phone 如果没有诺基亚，历史地位会低很多。

因为真正把这套系统从“软件方案”变成“有记忆点的平台形象”的，就是 Lumia。  
它让 Windows Phone 不只是界面截图好看，而是真正拥有：

- 鲜明的色彩和工业设计人格
- 影像和地图等可感知差异化
- 一批能代表时代审美的实体机型

诺基亚合作的意义，是把 Windows Phone 从“微软做系统”变成“微软终于有了像样的手机阵地”；  
收购的意义，则是把“阵地”变成“自己的最后主战场”。

但也正因为如此，诺基亚与微软的结合同时留下了一种非常强烈的悲剧感：  
两个都在时代转折中承压的巨头，试图相互借力，最终却没能在 iPhone 与 Android 的双重挤压中重建新秩序。

### 8.2 为什么它会成为“历史地位高于市场结果”的典型平台

因为它在三个层面都留下了真正有分量的遗产：

1. 设计遗产。  
Metro、Live Tiles、内容优先、强排版、动效叙事，这些都不是一次性花活。

2. 平台遗产。  
手机上的 Xbox LIVE、跨设备统一身份、统一商店、通用应用、手机即计算入口，这些命题后面都没有消失。

3. 教训遗产。  
平台战争里，设计不能替代生态；  
技术路线升级不能轻易割裂用户；  
“第三生态”不是靠口号就能建成；  
规模、开发者与头部应用是最硬的基本盘。

很多平台是失败后被迅速忘掉。  
Windows Phone 不是。  
它之所以一直被反复讨论，恰恰因为它失败得很有内容。

### 8.3 它到底留下了什么

它留下的，不只是 Lumia 机身和锁屏截图，不只是“当年那个很好看的开始菜单”，而是以下几件更重的东西：

- 一套在手机设计史上极有辨识度的系统语言
- 一次把主机网络、成就与手机游戏接起来的尝试
- 一段“系统体验优等生却输给生态”的经典平台史样本
- 一次微软从 `手机上的 Windows` 走向 `One Windows` 的完整实验
- 一个证明“未来感”和“市场结果”并不天然一致的案例

这就是它的历史价值。

---

## 9. 一句话总结

Windows Phone 最值得被记住的地方，不是它作为手机系统卖得多成功，而是它在 iPhone 与 Android 主宰的时代里，曾认真拿出过一套极有魅力、极有判断、也极有历史感的第三种答案；只是当平台战争最终回到应用生态、开发者回报和规模正循环时，它终究还是来晚了，也没等到自己的时代。

---

## 10. 参考资料

1. [Microsoft Announces Windows CE, Newest Member of Windows Family（1996-09-16）](https://news.microsoft.com/1996/09/16/microsoft-announces-windows-cenewest-member-of-windows-family/)
2. [Microsoft Reveals New Windows Phones With Marketplace and My Phone Services（2009-02-16）](https://news.microsoft.com/2009/02/16/microsoft-reveals-new-windows-phones-with-marketplace-and-my-phone-services/)
3. [Microsoft Unveils Windows Phone 7 Series（2010-02-15）](https://news.microsoft.com/2010/02/15/microsoft-unveils-windows-phone-7-series/)
4. [Introducing Windows Phone 7 Series（2010-02-15）](https://blogs.microsoft.com/blog/2010/02/15/introducing-windows-phone-7-series/)
5. [With Xbox LIVE and a Blockbuster Title Lineup, Windows Phone 7 Marks a New Era in Mobile Gaming（2010-08-16）](https://news.microsoft.com/2010/08/16/with-xbox-live-and-a-blockbuster-title-lineup-windows-phone-7-marks-a-new-era-in-mobile-gaming/)
6. [EA Mobile to Publish Games for Windows Phone 7（2010-10-11）](https://news.microsoft.com/source/2010/10/11/ea-mobile-to-publish-games-for-windows-phone-7/)
7. [Windows Phone 7 Goes on Sale in the United States（2010-11-08）](https://news.microsoft.com/2010/11/08/windows-phone-7-goes-on-sale-in-the-united-states-is-there-hope-for-people-in-need-of-better-phone-behavior/)
8. [Nokia and Microsoft Announce Plans for a Broad Strategic Partnership to Build a New Global Mobile Ecosystem（2011-02-10/11）](https://news.microsoft.com/source/2011/02/10/nokia-and-microsoft-announce-plans-for-a-broad-strategic-partnership-to-build-a-new-global-mobile-ecosystem/)
9. [Nokia and Microsoft Sign Definitive Agreement Ahead of Schedule（2011-04-21）](https://news.microsoft.com/2011/04/21/nokia-and-microsoft-sign-definitive-agreement-ahead-of-schedule/)
10. [The next version of Windows Phone has the sweet taste of “Mango”（2011-05-24）](https://blogs.microsoft.com/blog/2011/05/24/the-next-version-of-windows-phone-has-the-sweet-taste-of-mango/)
11. [Windows Phone 7.5 “Mango” update begins（2011-09-27）](https://blogs.windows.com/windowsexperience/2011/09/27/windows-phone-7-5-mango-update-begins/)
12. [New Windows Phones Hit Store Shelves Today（2011-11-07）](https://news.microsoft.com/2011/11/07/new-windows-phones-hit-store-shelves-today/)
13. [Announcing Windows Phone 8（2012-06-20）](https://blogs.windows.com/windowsexperience/2012/06/20/announcing-windows-phone-8/)
14. [Microsoft Unveils Windows Phone 8（2012-10-29）](https://news.microsoft.com/source/2012/10/29/microsoft-unveils-windows-phone-8/)
15. [Introducing Windows Phone 8（2012-10-29）](https://blogs.microsoft.com/blog/2012/10/29/introducing-windows-phone-8/)
16. [Windows Phone 7.8 - Microsoft Lifecycle](https://learn.microsoft.com/en-us/lifecycle/products/windows-phone-78)
17. [Microsoft unveils updates to Windows and Windows Phone at Build 2014（2014-04-02）](https://blogs.microsoft.com/blog/2014/04/02/microsoft-unveils-updates-to-windows-and-windows-phone-at-build-2014/)
18. [Microsoft announces Windows Phone 8.1 Update details（2014-07-30）](https://blogs.microsoft.com/blog/2014/07/30/windows-phone-8-1-update-cortana-markets/)
19. [Microsoft to acquire Nokia’s devices & services business, license Nokia’s patents and mapping services（2013-09-03）](https://news.microsoft.com/2013/09/03/microsoft-to-acquire-nokias-devices-services-business-license-nokias-patents-and-mapping-services/)
20. [Microsoft acquisition of Nokia Devices and Services business finalized（2014-04-25）](https://blogs.microsoft.com/blog/2014/04/25/microsoft-acquisition-of-nokia-devices-and-services-business-finalized/)
21. [Nokia completes sale of substantially all of its Devices & Services business to Microsoft（2014-04-25）](https://www.nokia.com/about-us/news/releases/2014/04/25/nokia-completes-sale-of-substantially-all-of-its-devices-services-business-to-microsoft/)
22. [A first look at the Windows 10 universal app platform（2015-03-02）](https://blogs.windows.com/windowsdeveloper/2015/03/02/a-first-look-at-the-windows-10-universal-app-platform/)
23. [Expanding the Universal Windows Platform at Build 2015（2015-04-29）](https://blogs.windows.com/windowsdeveloper/2015/04/29/expanding-the-universal-windows-platform-at-build-2015/)
24. [Build 2015 marks an important step in our journey with developers（2015-04-30）](https://blogs.microsoft.com/blog/2015/04/30/build-2015-marks-an-important-step-in-our-journey-with-developers-and-its-just-the-beginning/)
25. [Continuum on Windows 10（2015-07-27）](https://blogs.windows.com/windowsexperience/2015/07/27/continuum-on-windows-10/)
26. [Optimizing apps for Continuum for phone（2015-12-07）](https://blogs.windows.com/windowsdeveloper/2015/12/07/optimizing-apps-for-continuum-for-phone/)
27. [Continuum for Phones: Making the Phone Work Like a PC（2016-01-14）](https://blogs.windows.com/windowsexperience/2016/01/14/continuum-for-phones-making-the-phone-work-like-a-pc/)
28. [Microsoft announces restructuring of phone hardware business（2015-07-08）](https://news.microsoft.com/2015/07/08/microsoft-announces-restructuring-of-phone-hardware-business/)
29. [FY15 Q4 Press Release & Webcast（2015-07-21）](https://www.microsoft.com/en-us/Investor/earnings/FY-2015-Q4/press-release-webcast)
30. [Microsoft 2015 Annual Report](https://www.microsoft.com/investor/reports/ar15/index.html)
31. [Windows 10 Mobile End of Support（Microsoft Lifecycle）](https://learn.microsoft.com/en-us/lifecycle/announcements/windows-10-mobile-end-of-support)
32. [Windows Mobile 6.5 - Microsoft Lifecycle](https://learn.microsoft.com/en-us/lifecycle/products/windows-mobile-65)
33. [Windows Phone user experience design（Build 2011 / Microsoft Learn）](https://learn.microsoft.com/en-us/shows/build-build2011/app-832t)
34. [Designing Metro style: principles and personality（Build 2011 / Microsoft Learn）](https://learn.microsoft.com/en-us/shows/build-build2011/app-395t)
35. [Windows Phone - Design Your Windows Phone Apps to Sell（MSDN Magazine, 2012-01）](https://learn.microsoft.com/en-us/archive/msdn-magazine/2012/january/windows-phone-design-your-windows-phone-apps-to-sell)
36. [Metro Design Principles（Microsoft Research）](https://www.microsoft.com/en-us/research/video/metro-design-principles/)
37. [Microsoft unites Xbox and PC gamers with debut of Games for Windows - LIVE（2007-03-14）](https://news.microsoft.com/2007/03/14/microsoft-unites-xbox-and-pc-gamers-with-debut-of-games-for-windows-live/)
38. [Halo: Spartan Strike ya disponible（Microsoft News，2015-04-16）](https://news.microsoft.com/es-es/2015/04/16/halo-spartan-strike-ya-disponible/)
39. [Windows Mobile（Wikipedia）](https://en.wikipedia.org/wiki/Windows_Mobile)
40. [Windows CE（Wikipedia）](https://en.wikipedia.org/wiki/Windows_CE)
41. [Metro (design language)（Wikipedia）](https://en.wikipedia.org/wiki/Metro_%28design_language%29)
42. [Windows Phone review – 8.1 advances, but needs to close 'app gap'（The Guardian，2014-04-16）](https://www.theguardian.com/technology/2014/apr/16/windows-phone-review-81-iphone-android-microsoft)
43. [Snapchat cracks down on Windows Phone imitator apps（PCWorld，2014-12-22）](https://www.pcworld.com/article/430956/snapchat-cracks-down-on-windows-phone-imitator-apps.html)
44. [Microsoft pays “$100,000 or more” to get devs coding for Windows Phone（Ars Technica，2013-06-14）](https://arstechnica.com/information-technology/2013/06/microsoft-pays-100000-or-more-to-get-devs-coding-for-windows-phone/)

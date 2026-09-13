# 全站文案审计 · v0.3

日期：2026-09-13。范围：`E:\workbuddy-space\Entelina` 全部 41 个页面 + 生成器 + 内部文档。
审计标准：① 不与当前标志（八瓣放射）冲突；② 不虚构社区成就；③ 未实现的部分如实标注；④ 不写空泛形容词。

---

## 一、必须改：文案仍按旧标志（开放 A / 展翼 A / 字母 A）描述

新标志是八瓣放射展开的几何图形，与字母 A 无关。下列表述本来全部指向旧标志，属事实性错误。

| 文件 | 原文 | 改为 |
|---|---|---|
| `brand.html` | `alt="Entelina 开放 A"` | `alt="Entelina 标志"` |
| `brand.html` | 「连接创作的开放感与工具的秩序感」 | 直接描述标志结构：八片尖端朝内的楔形 + 断开的墨绿环带 |
| `brand.html` | 「统一使用墨绿、黑白与充足的留白」 | 深墨绿 / 纸白 / 琥珀 / 陶土；不使用渐变、投影与动画 |
| `brand.html` | 色板只有 2 色 | 扩为 4 色（补 #B4761C、#9C4A16），并补 `.swatch.amber/.clay` 样式 |
| `work-identity.html` | 「从一枚艺术字母，到一套…系统」 | 「从一枚八瓣放射的标志，到一套…系统」 |
| `work-identity.html` | 全篇 4 节讲「展翼 A / 新 A / 字母 A 母题」 | 4 节全部重写为标志结构、纯色构成、体系与待验证边界 |
| `work-identity.html` | `alt="Entelina 品牌字标与简化 A"` | `alt="Entelina 标志与字标"` |
| `work-unfolding.html` | 「从名字轻盈的发音出发」 | 语义残留自旧名 Aerulie（发音轻盈）；改为直接讲 entelecheia |
| `work-unfolding.html` | 「纸翼与字母 A 之间的形态」「象牙白纸翼」 | 「八片手工纸瓣从一点向外打开」 |
| `index.html` | `alt="静置于墨绿空间中的折纸 A 雕塑"` | `alt="深墨绿空间中向外展开的手工纸花瓣雕塑"` |
| `index.html` | hero 图注「开放，是创造的起点。」 | 「展开，是创造的起点。」 |
| `showcase.html` / `issue-000.html` | 「以折纸形态研究空气、结构与字母 A」「纸翼雕塑」「纸翼主视觉」 | 改为手工纸展开、结构 / 光线 / 对称 |
| `changelog.html` | v0.1「绘制展翼 A」「建立…展翼 A 习作」 | 「生成主视觉」「主视觉习作」 |
| `release-02.html` | 「主标志收拢装饰，配合稳定字标使用」 | 「标志与字标固定搭配」 |

## 二、必须改：虚构社区成就

| 文件 | 原文 | 问题 | 改为 |
|---|---|---|---|
| 导航 / `products.html` | 「社区共创工具与项目」「社区共创工具」 | 两款工具是 Entelina 自己开发的，不是社区共创产物 | 「本地工具与项目」「本地工具」 |
| `products.html` | 「CO-CREATED PRODUCTS …让社区的实践与想法成为可使用、可维护的产品」 | 同上 | 「PRODUCTS / LOCAL TOOLS …两款在浏览器本地运行的工具」 |
| `products.html` | 分节标题「BUILD WITH THE COMMUNITY」 | 社区尚未成形 | 「HOW A TOOL GETS MADE」 |
| `developers.html` | 「参与社区项目」「准备你的社区产品提案」 | 没有已存在的社区项目 | 「准备一份提案」「准备你的项目提案」 |
| `showcase.html` | 页面标题「社区作品」 | 只有 Entelina 自己的 2 项习作 | 标题改「作品」 |
| `showcase.html` | 「按期呈现社区作品」 | 同上 | 「按期呈现 Entelina 的作品」 |
| `editions.html` | 「按期归档社区优秀作品」 | 「优秀」暗示评选 | 「按期归档 Entelina 的作品」 |
| `community.html` | 「以具体问题相遇，以可分享的成果连接」（陈述语气） | 暗示交流已在进行 | 「社区正在筹备中。我们希望以…」 |
| `index.html` | hero「让一个人的灵感，成为所有人都能继续构建的起点」 | 空，且暗示已有人群 | 「一个正在筹备的 AI 共创社区。已经做出两款可以立刻使用的本地工具。」 |
| `community.html` | FAQ 缺「当前状态」 | — | 新增一问：正在筹备中，账号 / 投稿 / 讨论尚未开放，无开放时间表 |

**保留的判断**：`contribute.html`、`docs-start.html`、`docs-publishing.html`、`guidelines.html`、`roadmap.html`、
`privacy.html`、`developers.html` 的 notice 原本已如实说明「尚未开放」「不表示已有运营团队」「没有承诺开放日期」，
属正确表述，未改动。

## 三、建议改：注水表述

| 文件 | 原文 | 问题 | 改为 |
|---|---|---|---|
| `about.html` | 「艺术帮助我们看到新的可能，工程帮助我们把可能变成稳定的体验。」 | 抽象、可套在任何公司 | 「审美决定一件事物让人愿不愿意靠近，方法决定它能不能被反复使用。」 |
| `issue-000.html` | 「在形态、语言与秩序之间，为共同的创造找到一个起点。」 | 堆砌名词 | 「两项品牌习作，记录 Entelina 从一枚标志到一套视觉系统的过程。」 |
| `index.html` | 「Entelina 为这些不同的贡献准备共同的入口。」 | 暗示入口已存在 | 「Entelina 正在为这些不同的贡献准备入口。」 |

## 四、同步与留痕

- 新增 `release-03.html`（changelog v0.3）。更新日志自己承诺「记录每一次变化」，标志换代与文案修订应有记录。
- `README.md`、`AGENTOS-DELIVERY-REPORT.md`、`research/site-architecture.md` 同步（页数 40 → 41、标志描述、旧稿存档位置）。
- `research/brand-and-site-review.md` **末尾追加变更记录，不删原判断**——研究记录应留痕；同时写明上一轮两个技术问题
  （SVG 是位图外壳、`logo-v1.svg` 被误覆盖）与「未做商标检索、不能据此认为可独占」的边界。

## 五、本次一并修掉的资产问题

1. `logo-*.svg` 原为「128px 位图 base64 塞进 SVG 外壳」（`n_path=0 / n_image=1`），不是矢量，导航栏 34px 下发糊。
   已用参数化几何重建为真矢量；PNG 侧以同一套参数 4 倍超采样重绘。
2. `assets/identity-cover.svg` 同样是位图外壳，已重写为纯矢量。
3. 目录里 5 张 `*-preview.png` 是 logo 替换**之前**生成的截图，左上角仍是 "A Aerulie"。已按 1440 / 390 视口全部重新生成。
4. 清理：移除调试用 `_preview_*.png`；把 `styles.css.bak` 与已失效的 `AGENTOS-ARTIFACT-QA.json`
   （路径指向 `E:\Codex\2026-09-12\gei\work\Entelina-v2`、字节数全部过期）移出到 `E:\workbuddy-space\_tools\`。

## 六、仍待决定（未擅自改动）

- 站点信息架构仍以「社区 / 共创 / 作品区」为框架。本次只把措辞改为如实，**没有改结构**。
  若社区长期停留在筹备状态，可考虑进一步弱化社区框架，或把它明确写成「筹建中，欢迎加入」。
- 站内**未**公布创始人数、校内属性、任何时间表。若你希望公开，需你确认口径。
- 第 000 期样刊的定位是「Entelina 自己的品牌习作」，属实；但若想让它更明确地不占用「期刊」语义，
  可考虑改叫「作品集」。未动。

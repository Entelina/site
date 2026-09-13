# Entelina 信息架构与后续建设

## 定位
产品、作品与知识构成三类成果，社区连接贡献者。研究者提供方法与证据，开发者实现工具，设计和创作者探索表达，编辑把经验整理为可持续阅读的内容。

## 当前网站：41 个独立页面
公共顶部菜单由 build.cjs 统一生成，不依赖浏览器脚本加载。下列页面均已实现，内容不是空白占位。

| 页面 | 文件 | 所属 |
|---|---|---|
| 共同探索，持续创造 | index.html | home |
| 产品 | products.html | products |
| 作品 | showcase.html | showcase |
| 期刊归档 | editions.html | showcase |
| 第 000 期 · 展开 | issue-000.html | showcase |
| 资源中心 | resources.html | resources |
| 文档 | docs.html | resources |
| Entelina 用例 | use-cases.html | resources |
| 实用手册 | handbook.html | resources |
| 开发者案例展示 | developer-showcase.html | resources |
| 开发者博客 | developer-blog.html | resources |
| Entelina 更新日志 | changelog.html | resources |
| 开发者入口 | developers.html | resources |
| 社区 | community.html | community |
| 关于 Entelina | about.html | about |
| 品牌资产 | brand.html | about |
| 搜索 | search.html | resources |
| 页面未找到 | 404.html | home |
| Brief · 创作简报 | product-brief.html | products |
| Index · 文档结构 | product-index.html | products |
| 准备共创提案 | contribute.html | community |
| 第一次来到 Entelina | docs-start.html | resources |
| Brief 与 Index 使用说明 | docs-products.html | resources |
| 产品与作品发布指南 | docs-publishing.html | resources |
| 从想法到创作简报 | case-brief.html | resources |
| 为长文档建立阅读地图 | case-reading.html | resources |
| 一份清晰提示的四个部分 | handbook-prompt.html | resources |
| 如何给出有用的作品反馈 | handbook-review.html | resources |
| 一个无构建依赖的多页面官网 | devcase-static.html | resources |
| 从 Markdown 到结构索引 | devcase-markdown.html | resources |
| 先让工具在本地成立 | blog-local.html | resources |
| AI 产品的秩序感来自哪里 | blog-design.html | resources |
| 展开 / The Unfolding | work-unfolding.html | showcase |
| 共同的标记 / A Shared Mark | work-identity.html | showcase |
| 发布与交流规范 | guidelines.html | community |
| 发展路线 | roadmap.html | community |
| 隐私与本地数据 | privacy.html | about |
| 多页面官网初版 | release-02.html | resources |
| 品牌与首页初稿 | release-01.html | resources |
| 标志与说明修订 | release-03.html | resources |
| 网站地图 | sitemap.html | about |

## 三条关键路径
1. 使用者：产品总览 → 工具 → 使用文档 / 用例。
2. 创作者：作品展示 → 期刊 → 作品过程 → 发布规范 / 提案。
3. 开发者：资源 → 案例 / 博客 → 产品 → 共创提案。

## 后续内容模型
- Product：id、slug、名称、说明、负责人、版本、状态、入口、仓库、许可、限制、文档。
- Work：id、作者、标题、媒体、描述、工具、过程、授权、所属期刊。
- Edition：期次、主题、日期、封面、编辑说明、作品引用、评选说明。
- Resource：类型（六类之一）、标题、作者、正文、标签、版本、更新时间、引用。
- Contributor：作者标识、展示名、个人简介、贡献项目、可公开联系入口。
- Proposal：提案类型、项目说明、当前成果、授权、审核状态、处理记录。

## 必须先补齐的真实运营环节
- 内容后台与作者资料：让非开发者能够维护产品、期刊和文章。
- 投稿接收与审核：区分草稿、提交、需补充、通过、发布；提供通知与撤回方式。
- 账号与隐私机制：明确运营主体、数据处理、删除和授权范围。
- 期刊编辑流程：实际确定主题、编辑、评选标准与作者确认。
- 产品维护：版本、维护者与问题反馈入口。

本次没有擅自接入账号、收费、模型 API 或公网服务，也没有伪造已上线社区状态。上述属于下一阶段开发，已在界面中清楚表达现状。

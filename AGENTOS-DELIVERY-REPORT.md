# Entelina 第二版交付与验证

日期：2026-09-13。v0.3 修订：换用八瓣放射展开的矢量主标志，并全站修订与旧标志绑定的文案、清理与实际情况不符的社区表述。详见 release-03.html 与 research/brand-and-site-review.md 末节。

## 交付结果

41 个独立 HTML 页面，共用顶部菜单与页脚，支持直接双击 index.html。包含产品及可用本地工具、作品与期刊、六类资源、开发者入口、社区贡献、规范、路线、关于、品牌、隐私、搜索和站点地图。页面内容与导航由 build.cjs 统一生成，修改方法见 README.md。

品牌提供矢量 SVG、透明 PNG、深浅背景头像、512px 头像与 32px 站点图标。静态视觉使用纸白、深墨绿、琥珀与陶土，配八瓣放射展开的主标志与完整字标。完整品牌适配与公开相似性研究见 research/brand-and-site-review.md；信息架构见 research/site-architecture.md。

## 验证证据

- Chrome + Playwright 检查全部 40 页，1440、390、320px 宽度无横向溢出。
- 所有内部文件链接、锚点、图片加载、HTTP 状态及单一 H1 检查通过；无 JavaScript 错误。
- 无 CSS 动画、过渡、平滑滚动或 JavaScript 动画循环；运行时动画数为零。
- 桌面和手机共用菜单、Escape 关闭、搜索、空结果、作品筛选验证通过。
- Brief 输入校验与 Markdown 下载、Index 标题层级和代码围栏处理及下载、贡献提案本地导出均通过。
- file:// 下搜索与工具可用；额外验证 Index 保留开头空行后的原始行号。
- 人工查看首页、资源页、工具页、作品页、文章、菜单及手机截图；修复图片高度问题后重新检查全部页面。
- 查看品牌预览中的深浅头像、圆形裁切与 48/32/24/16px 尺寸。最终手机标题平衡换行已单独截图复核。

结构化检查结果：research/qa-results.json。最终预览：homepage-preview.png、mobile-preview.png、brand-preview.png、resources-preview.png、showcase-preview.png。

## 交付边界

这是可运行的静态官网初始版本，未部署，未接入账号、数据库、实际在线投稿或模型服务。两款工具在浏览器本地执行确定性文本处理。提案表单只导出文件，不会提交到服务器。作品第 000 期为明确标注的品牌样刊，不虚构社区评选、用户数量或企业历史。

Logo 公开检索未确认高度近似轮廓，但检索有限，未完成反向图片检索或完整商标数据库审查，不能保证唯一或替代商标查重。旧版标志留存于 research/logo-v1.svg。

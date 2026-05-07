# Binghill.com 品牌展示站 — 项目档案

> 建立时间：2026-05-07
> 最后更新：2026-05-07

---

## 一、项目概述

**项目名称：** Binghill 品牌独立站
**域名：** binghill.com
**类型：** 品牌展示网站（非电商站，导向 Amazon 销售）
**目标用户：** 美国户外运动爱好者、户外冒险场景用户
**核心功能：** 品牌故事展示、产品理念传达、导流至 Amazon 店铺

---

## 二、已知品牌信息

### 品牌定位
- **品牌名：** Binghill
- **品类：** Oversized Insulated Drinkware（大容量保温杯/壶）和 Coolers（保温箱）
- **Slogan：** Where Nature and Innovation Unite
- **目标场景：** 徒步、露营、车尾派对（tailgate party）、运动场等户外冒险

### 产品核心卖点
- 50oz+ 大容量
- 24小时保冰（24-hour ice retention）
- BPA-free、食品级不锈钢
- Adventure-proof（冒险级耐用）
- Leak-resistant（防漏设计）

### 品牌故事（摘要）
> "Binghill 的想法来自一个简单的挫败感：我们依赖的户外装备要么无聊、要么脆弱、要么太小。我们需要足够大的杯子来支撑一整天的徒步，能在太阳下放几小时后仍然喝起来清爽，能经受无数次被扔进卡车后斗的折腾。"

### 销售渠道
- 主要：Amazon Store（https://www.amazon.com/stores/Binghill）
- 独立站定位：品牌展示，不直接交易

---

## 三、当前网站结构

```
binghill-site/
├── index.html          # 首页 / Our Story 页面
├── story.html          # 品牌故事（当前为占位页，仅跳转链接）
├── what-we-do.html     # 产品理念页
├── logo_v2_web.png     # 网站用 Logo
├── logo_transparent.png
├── logo_v2_transparent.png
├── story-images/       # 品牌故事图片素材
└── .git/               # Git 版本管理
```

### 页面说明
| 页面 | 当前状态 | 说明 |
|------|---------|------|
| index.html | 完整 | Our Story 首页，完整的品牌叙事内容 |
| story.html | 最小化 | 仅为导航占位，跳转链接 |
| what-we-do.html | 完整 | Where Nature and Innovation Unite，展示产品理念 |

### 技术栈
- 纯 HTML + CSS + Vanilla JS（无框架）
- Google Fonts（Inter）
- 响应式设计（移动端适配）
- 固定导航栏 + 滚动变色效果

---

## 四、技术现状与待办

### 已完成
- [x] 基础页面结构搭建（index、story、what-we-do）
- [x] 品牌 Logo 确认（v2 版本）
- [x] 导航栏滚动动效
- [x] 移动端 hamburger 菜单
- [x] 品牌故事内容填充
- [x] Amazon 店铺 CTA 链接集成

### 待完成 / 待迭代
- [ ] **产品展示页**（当前缺失专门的 Products 页面）
- [ ] **Contact / 联系我们页**
- [ ] **FAQ 页**（用户常见问题）
- [ ] **网站图标**（favicon、apple-touch-icon）
- [ ] **SEO 优化**（Open Graph、Twitter Card、结构化数据）
- [ ] **页面速度优化**（图片压缩、懒加载）
- [ ] **多语言版本**（英文为主，是否需要中文版待确认）
- [ ] **网站分析**（Google Analytics / Pixels 集成）
- [x] **域名绑定 + HTTPS**（已通过 Cloudflare 配置）
- [x] **正式上线确认**（已部署，域名已解析）
- [x] **代码托管与发布**（通过 GitHub 实时上传发布）

---

## 五、协作记录

### 2026-05-06
- 初始构建：index.html + story.html 双页面结构
- 重构调整：Our Story 内容移至 index，原 index 改为 What We Do
- 导航链接：Our Story / What We Do / Shop on Amazon

### 2026-05-07
- 项目正式建立独立档案
- 需求待与 Binghill 确认后更新
- 域名 binghill.com 已通过 Cloudflare 配置完成
- 网站已部署上线
- 部署方式：代码推送至 GitHub，实时发布

### 2026-05-07（来自 main session 的上下文传递）
- 用户反馈"还是不行"——**具体哪个页面/哪个功能待确认**
- 用户要求建立独立项目并持续迭代，避免 session 丢失
- 已建立：PROJECT.md、memory/2026-05-07.md、MEMORY.md 更新

## 六、用户反馈追踪

### 🔴 用户表示"还是不行"
> 具体问题尚未明确，需要进一步诊断。
> 可能涉及：页面显示问题、链接失效、功能异常等。
> **待向用户确认具体症状。**

---

## 七、待确认需求

> 以下内容需与 Binghill 沟通确认后再填入：

1. **网站是否需要多语言版本？**（目前全英文）
2. **是否需要产品展示页？**（当前无专门产品页）
3. **是否有 Instagram / Social 链接需要加入 footer？**
4. **Contact 页面形式：** 邮箱？表单？微信？
5. **是否需要 Blog / News 栏目？**
6. **网站是否需要后台 CMS？**（目前纯静态）
7. ~~**域名是否已注册？** 托管在哪里？~~ ✅ 已通过 Cloudflare 配置
8. **正式上线时间节点？**

### ⚠️ 优先确认项（来自 main session 分析）
- **"还是不行"具体指什么？**——这是最高优先级的诊断问题

---

## 八、相关文件路径

- 项目目录：`/Users/mini/.openclaw/workspace/binghill-site/`
- 本项目文档：`/Users/mini/.openclaw/workspace/binghill-site/PROJECT.md`
- 品牌规范：`/Users/mini/.openclaw/workspace/binghill-site/BRAND.md`（待建立）
- 技术规范：`/Users/mini/.openclaw/workspace/binghill-site/TECH.md`（待建立）

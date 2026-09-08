# 🎬 TikTok Shop 爆款带货视频提示词库

[![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)
[![GitHub stars](https://img.shields.io/github/stars/Clipcat-ai/awesome-tiktok-shop-video-prompts?style=social)](https://github.com/Clipcat-ai/awesome-tiktok-shop-video-prompts)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](./LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./CONTRIBUTING.md)

**English → [README.md](./README.md)**

**647 条从真实 TikTok Shop 带货视频反推出来的提示词** —— 每一条都是它所在市场 × 品类当周的榜首。不是人手编的提示词：每条都是对一个真正卖出货的视频的逐镜头还原，原视频链接就附在旁边，可以自己核对。

> 🤖 想让你的 AI agent 直接检索这个库、针对**你自己的产品**产出一条能开拍的提示词？ 👉 [clipcat-skill](https://github.com/Clipcat-ai/clipcat-skill)

---

## 每条包含什么

`prompts/<市场>/<品类>/` 下每个文件是一条：

- **中英双语提示词** —— 风格、环境、节奏、镜头、灯光、人物，然后是带时间轴和口播的逐镜头拆解；
- **开场那一下** —— 视频开场说的那句话（原文是英文的照引，不是英文的给英译），以及它打的痛点；
- **结构化标签** —— 视频形态、钩子类型、出镜情况、促销机制、口播语言；
- **原 TikTok 视频链接**，提示词描述的是什么，可以直接看。

我们不转发视频、封面、商品图和销售数据。见 [NOTICE.md](./NOTICE.md)。

> **这是一份快照。** 共 647 条，取自截至 **2026-08-31** 的周榜。
> 底库每周都在涨，[完整库在 clipcat.ai 上可检索](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt?utm_source=github&utm_medium=repo&utm_campaign=prompt-library)；本仓库按批次刷新，不是实时同步。

### 一条长什么样

<details open>
<summary><b>Cordless Tyre Inflator Air… — Real Review (United Kingdom · Tools & Hardware)</b> — <code>gb-tools-463382</code></summary>

```text
[Style]: 写实硬核种草风，采用真实户外实拍场景，画面色彩鲜活明快，产品功能展示直观清晰，自带海外汽车好物分享的真实感与说服力。
[Environment]: 多场景无缝切换的真实户外与居家环境，涵盖沙漠沙地、城市街边泊车位、居民后院草坪、露天停车场、居家客厅地板等，晴天自然光充足，不同场景下光线明亮通透，完整覆盖车载充气泵的全使用场景。

Shot 1:
  - 时长: 0.0sec - 3.0sec
  - 镜头类型: 设置问题
  - 画面: 沙漠沙地场景中，一辆哑光黑色硬派越野停在沙地上，轮胎处于亏气状态。一只手握着黑色手持充气泵，将气管连接到越野车轮胎的气门嘴，镜头从轮胎侧面缓缓推进，清晰展示轮胎从瘪状态逐渐恢复饱满的过程。画面顶部叠加白色标题文字，底部标注视频内容已加速的说明文字。
  - 口播: Ever thought about how much money you spend on petrol station air?
…
```

[看完整条目 →](./prompts/gb/tools-hardware/gb-tools-463382.md) · [看原视频 →](https://www.tiktok.com/share/video/7614465584268463382)

</details>

---

## 怎么用

**配任意视频模型用。** 把中文或英文提示词粘进 Sora 2、Veo 3、可灵、Seedance 或你在用的模型。提示词是模型无关的自然语言，真正关键的是镜头表。

**换成你自己的产品。** 提示词描述的是别人的产品。把产品名词和口播换掉，**结构留着** —— 卖货的是结构。

**配 Clipcat 用。** 每条都链到 [clipcat.ai](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) 上的同一条提示词，在那儿可以直接传自己的产品图一键复刻。

---

## 提示词格式

每个区块什么意思、为什么这么切，见 [docs/prompt-format.md](./docs/prompt-format.md)；13 种开场钩子和 13 种视频形态的定义见 [docs/hook-taxonomy.md](./docs/hook-taxonomy.md)。

---

### 按市场浏览

| 市场 | 条数 | 市场 | 条数 |
| --- | ---: | --- | ---: |
| [🇸🇬 新加坡](./prompts/sg) | 52 | [🇬🇧 英国](./prompts/gb) | 44 |
| [🇺🇸 美国](./prompts/us) | 51 | [🇯🇵 日本](./prompts/jp) | 44 |
| [🇧🇷 巴西](./prompts/br) | 50 | [🇻🇳 越南](./prompts/vn) | 42 |
| [🇲🇾 马来西亚](./prompts/my) | 48 | [🇪🇸 西班牙](./prompts/es) | 37 |
| [🇵🇭 菲律宾](./prompts/ph) | 48 | [🇩🇪 德国](./prompts/de) | 35 |
| [🇮🇩 印度尼西亚](./prompts/id) | 46 | [🇮🇹 意大利](./prompts/it) | 31 |
| [🇲🇽 墨西哥](./prompts/mx) | 46 | [🇫🇷 法国](./prompts/fr) | 27 |
| [🇹🇭 泰国](./prompts/th) | 46 |  |  |

### 按品类浏览

| 品类 | 条数 | 品类 | 条数 |
| --- | ---: | --- | ---: |
| [鞋靴](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-shoes?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 29 | [工具与五金](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-tools--hardware?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 24 |
| [女装与内衣](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-womenswear--underwear?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 29 | [时尚配饰](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-fashion-accessories?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 23 |
| [健康保健](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-health?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 28 | [食品与饮料](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-food--beverages?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 23 |
| [美妆与个护](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-beauty--personal-care?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 26 | [家具](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-furniture?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 23 |
| [居家用品](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-home-supplies?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 26 | [厨房用品](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-kitchenware?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 23 |
| [男装与内衣](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-menswear--underwear?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 26 | [图书音像](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-books-magazines--audio?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 22 |
| [玩具与爱好](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-toys--hobbies?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 26 | [手机与数码](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-phones--electronics?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 22 |
| [汽车与摩托](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-automotive--motorcycle?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 25 | [运动与户外](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-sports--outdoor?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 22 |
| [家装建材](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-home-improvement?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 25 | [母婴用品](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-baby--maternity?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 21 |
| [家用电器](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-household-appliances?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 25 | [收藏品](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-collectibles?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 20 |
| [电脑与办公](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-computers--office-equipment?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 24 | [童装](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-kids-fashion?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 16 |
| [珠宝首饰](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-jewelry-accessories--derivatives?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 24 | [穆斯林时尚](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-muslim-fashion?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 10 |
| [箱包](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-luggage--bags?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 24 | [二手](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-pre-owned?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 9 |
| [宠物用品](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-pet-supplies?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 24 | [预订与代金券](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-bookings--vouchers?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 2 |
| [纺织与软装](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-textiles--soft-furnishings?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 24 | [虚拟商品](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-virtual-products?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 2 |

### 按视频形态浏览

| 形态 | 条数 | 形态 | 条数 |
| --- | ---: | --- | ---: |
| [手持商品展示](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/type-handheld-demo?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 245 | [OOTD穿搭展示](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/type-ootd?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 37 |
| [真实使用测评](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/type-real-review?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 107 | [互动剧情演绎](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/type-story-skit?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 12 |
| [促销卖点强推](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/type-promo-pitch?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 80 | [品牌短TVC](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/type-brand-tvc?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 7 |
| [口播介绍](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/type-talking-head?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 53 | [第一人称开箱](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/type-unboxing-pov?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 4 |
| [场景化生活秀](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/type-lifestyle-scene?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 53 | [多品横向对比](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/type-product-compare?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 2 |
| [产品镜头特写](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/type-product-closeup?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 45 | [ASMR感官沉浸](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/type-asmr?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 2 |

### 按开场钩子浏览

| 钩子 | 条数 | 钩子 | 条数 |
| --- | ---: | --- | ---: |
| [结果先行](./docs/hook-taxonomy.md#opening-hooks) | 197 | [剧情冲突](./docs/hook-taxonomy.md#opening-hooks) | 12 |
| [场景代入](./docs/hook-taxonomy.md#opening-hooks) | 159 | [反常识反差](./docs/hook-taxonomy.md#opening-hooks) | 9 |
| [痛点直击](./docs/hook-taxonomy.md#opening-hooks) | 120 | [身份认同](./docs/hook-taxonomy.md#opening-hooks) | 8 |
| [利益直给](./docs/hook-taxonomy.md#opening-hooks) | 59 | [效果对比](./docs/hook-taxonomy.md#opening-hooks) | 3 |
| [悬念好奇](./docs/hook-taxonomy.md#opening-hooks) | 56 | [沉浸感官](./docs/hook-taxonomy.md#opening-hooks) | 2 |
| [促销紧迫感](./docs/hook-taxonomy.md#opening-hooks) | 22 |  |  |

---

## 机器可读数据

`data/prompts.jsonl` —— 一行一个 JSON，字段与文件头一致，外加中英双语提示词全文。给 agent 或 RAG 索引吃的，不是给人读的。

## 参与贡献

给我们**视频链接**，不是提示词 —— 反推交给我们的流水线，署名归原作者。已有条目的纠错非常欢迎。见 [CONTRIBUTING.md](./CONTRIBUTING.md)。

## 许可

提示词按 [CC BY 4.0](./LICENSE) 发布，署名格式 `Prompts from Awesome TikTok Shop Video Prompts by Clipcat, CC BY 4.0`。从原视频引用的口播台词、以及我们对它的翻译，**都不在授权范围内**，版权归原作者。商用前请先读 [NOTICE.md](./NOTICE.md)。

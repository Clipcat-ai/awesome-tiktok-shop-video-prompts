<a href="https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt?utm_source=github&utm_medium=repo&utm_campaign=prompt-library">
  <img src="https://static.clipcat.ai/site/og/viral-prompt-library-zh.png" alt="TikTok Shop 爆款带货视频提示词库" width="100%" />
</a>

# 🎬 TikTok Shop 爆款带货视频提示词库

[![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)
[![GitHub stars](https://img.shields.io/github/stars/Clipcat-ai/awesome-tiktok-shop-video-prompts?style=social)](https://github.com/Clipcat-ai/awesome-tiktok-shop-video-prompts)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](./LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./CONTRIBUTING.md)

**English → [README.md](./README.md)**

**684 条从真实 TikTok Shop 带货视频反推出来的提示词** —— 每一条都是它所在市场 × 品类当周的榜首。不是人手编的提示词：每条都是对一个真正卖出货的视频的逐镜头还原，原视频链接就附在旁边，可以自己核对。

> 🤖 想让你的 AI agent 直接检索这个库、针对**你自己的产品**产出一条能开拍的提示词？ 👉 [clipcat-skill](https://github.com/Clipcat-ai/clipcat-skill)

---

## 每条包含什么

`prompts/<市场>/<品类>/` 下每个文件是一条：

- **中英双语提示词** —— 风格、环境、节奏、镜头、灯光、人物，然后是带时间轴和口播的逐镜头拆解；
- **开场白原文**，以及它打的痛点；
- **结构化标签** —— 视频形态、钩子类型、出镜情况、促销机制、口播语言；
- **原 TikTok 视频链接**，提示词描述的是什么，可以直接看。

我们不转发视频、封面、商品图和销售数据。见 [NOTICE.md](./NOTICE.md)。

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
| [🇸🇬 新加坡](./prompts/sg) | 54 | [🇲🇽 墨西哥](./prompts/mx) | 46 |
| [🇲🇾 马来西亚](./prompts/my) | 53 | [🇻🇳 越南](./prompts/vn) | 46 |
| [🇺🇸 美国](./prompts/us) | 53 | [🇬🇧 英国](./prompts/gb) | 44 |
| [🇵🇭 菲律宾](./prompts/ph) | 52 | [🇪🇸 西班牙](./prompts/es) | 38 |
| [🇧🇷 巴西](./prompts/br) | 50 | [🇩🇪 德国](./prompts/de) | 37 |
| [🇹🇭 泰国](./prompts/th) | 50 | [🇮🇹 意大利](./prompts/it) | 35 |
| [🇮🇩 印度尼西亚](./prompts/id) | 48 | [🇫🇷 法国](./prompts/fr) | 32 |
| [🇯🇵 日本](./prompts/jp) | 46 |  |  |

### 按品类浏览

| 品类 | 条数 | 品类 | 条数 |
| --- | ---: | --- | ---: |
| [ 鞋靴](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-shoes?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 30 | [ 箱包](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-luggage-bags?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 25 |
| [ 女装与内衣](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-womenswear-underwear?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 29 | [ 汽车与摩托](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-automotive-motorcycle?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 24 |
| [ 健康保健](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-health?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 28 | [ 家具](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-furniture?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 24 |
| [ 美妆与个护](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-beauty-personal-care?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 27 | [ 童装](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-kids-fashion?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 24 |
| [ 男装与内衣](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-menswear-underwear?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 27 | [ 厨房用品](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-kitchenware?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 24 |
| [ 玩具与爱好](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-toys-hobbies?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 27 | [ 宠物用品](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-pet-supplies?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 24 |
| [ 母婴用品](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-baby-maternity?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 26 | [ 手机与数码](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-phones-electronics?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 24 |
| [ 电脑与办公](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-computers-office-equipment?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 26 | [ 纺织与软装](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-textiles-soft-furnishings?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 24 |
| [ 食品与饮料](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-food-beverages?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 26 | [ 工具与五金](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-tools-hardware?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 24 |
| [ 家装建材](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-home-improvement?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 26 | [ 图书音像](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-books-magazines-audio?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 23 |
| [ 居家用品](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-home-supplies?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 26 | [ 收藏品](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-collectibles?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 22 |
| [ 运动与户外](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-sports-outdoor?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 26 | [ 穆斯林时尚](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-muslim-fashion?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 10 |
| [ 时尚配饰](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-fashion-accessories?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 25 | [ 二手](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-pre-owned?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 9 |
| [ 家用电器](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-household-appliances?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 25 | [ 预订与代金券](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-bookings-vouchers?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 2 |
| [ 珠宝首饰](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-jewelry-accessories-derivatives?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 25 | [ 虚拟商品](https://clipcat.ai/zh/tools/ai-tiktok-videos-prompt/browse/cat-virtual-products?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 2 |

### 按视频形态浏览

| 形态 | 条数 | 形态 | 条数 |
| --- | ---: | --- | ---: |
| 手持商品展示 | 264 | 互动剧情演绎 | 13 |
| 真实使用测评 | 113 | 品牌短TVC | 7 |
| 促销卖点强推 | 77 | null | 5 |
| 场景化生活秀 | 56 | 第一人称开箱 | 4 |
| 口播介绍 | 53 | 多品横向对比 | 2 |
| 产品镜头特写 | 48 | ASMR感官沉浸 | 2 |
| OOTD穿搭展示 | 40 |  |  |

### 按开场钩子浏览

| 钩子 | 条数 | 钩子 | 条数 |
| --- | ---: | --- | ---: |
| 结果先行 | 205 | 平铺开场 | 17 |
| 场景代入 | 169 | 剧情冲突 | 13 |
| 痛点直击 | 122 | 身份认同 | 9 |
| 利益直给 | 58 | 反常识反差 | 9 |
| 悬念好奇 | 56 | 效果对比 | 3 |
| 促销紧迫感 | 21 | 沉浸感官 | 2 |

---

## 机器可读数据

`data/prompts.jsonl` —— 一行一个 JSON，字段与文件头一致，外加中英双语提示词全文。给 agent 或 RAG 索引吃的，不是给人读的。

## 参与贡献

给我们**视频链接**，不是提示词 —— 反推交给我们的流水线，署名归原作者。已有条目的纠错非常欢迎。见 [CONTRIBUTING.md](./CONTRIBUTING.md)。

## 许可

提示词按 [CC BY 4.0](./LICENSE) 发布。从原视频引用的口播台词**不在授权范围内**，版权归原作者。商用前请先读 [NOTICE.md](./NOTICE.md)。

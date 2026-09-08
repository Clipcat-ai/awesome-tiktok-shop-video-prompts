# 🎬 Awesome TikTok Shop Video Prompts

[![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)
[![GitHub stars](https://img.shields.io/github/stars/Clipcat-ai/awesome-tiktok-shop-video-prompts?style=social)](https://github.com/Clipcat-ai/awesome-tiktok-shop-video-prompts)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](./LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./CONTRIBUTING.md)

**中文 → [README_ZH.md](./README_ZH.md)**

**647 prompts reverse-engineered from real TikTok Shop selling videos** — every one of them ranked #1 in its market and category for the week it went viral. Not hand-written prompts: each is a shot-by-shot reconstruction of a video that actually moved product, with the original video linked so you can check our work.

> 🤖 Want your AI agent to search this library and write a ready-to-shoot prompt for *your* product? 👉 [clipcat-skill](https://github.com/Clipcat-ai/clipcat-skill)

---

## What is in each entry

Every file under `prompts/<market>/<category>/` holds one entry:

- **the prompt, in English and Chinese** — style, environment, pacing, camera, lighting, cast, then a shot-by-shot breakdown with timings and spoken lines;
- **the opening beat** — the line the video opens on (quoted verbatim when it was spoken in
  English, translated when it was not) and the pain point it attacks;
- **structured labels** — video format, hook type, who is on camera, promo mechanism, voiceover language;
- **a link to the original TikTok video**, so you can watch what the prompt describes.

We do not redistribute the videos, cover images, product photos or sales figures. See [NOTICE.md](./NOTICE.md).

> **This is a snapshot.** 647 entries, drawn from weekly rankings up to
> **2026-08-31**. The underlying library grows every week and is [searchable in full on
> clipcat.ai](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt?utm_source=github&utm_medium=repo&utm_campaign=prompt-library); this repository is refreshed in batches, not continuously.

### What one looks like

<details open>
<summary><b>Cordless Tyre Inflator Air… — Real Review (United Kingdom · Tools & Hardware)</b> — <code>gb-tools-463382</code></summary>

```text
[Style]: Realistic hardcore product recommendation style, using real outdoor on-location shooting scenes, with vivid and bright picture colors, intuitive and clear product function demonstrations, bringing the authenticity and persuasiveness of overseas car good item sharing content.
[Environment]: Seamlessly switching between real outdoor and home environments, covering desert sand ground, city street parking spots, residential backyard lawn, open-air parking lot, home living room floor and more. Sufficient natural light on sunny days, bright and transparent lighting in all scenes, fully covering all usage scenarios of the car-mounted air pump.

Shot 1:
  - Duration: 0.0sec - 3.0sec
  - Scene Type: Setting the pressure value
  - Scene: In a desert sand scene, a matte black off-road vehicle is parked on the sand with its tire underinflated. A hand holds a black handheld air pump, connecting the air hose to the tire valve of the off-road vehicle. The camera slowly pushes in from the side of the tire, clearly showing the process of the tire gradually recovering from a deflated state to full. White title text is overlaid at the top of the frame, and explanatory text indicating that the video content has been accelerated is marked at the bottom.
  - Subject: Ever thought about how much money you spend on petrol station air?
…
```

[Read the full entry →](./prompts/gb/tools-hardware/gb-tools-463382.md) · [Watch the original video →](https://www.tiktok.com/share/video/7614465584268463382)

</details>

---

## How to use these

**With any video model.** Copy the English or Chinese prompt into Sora 2, Veo 3, Kling, Seedance or whatever you run. The prompts are model-agnostic prose; the shot list is the part that matters.

**Swap in your own product.** The prompts describe someone else's product. Replace the product nouns and the spoken lines, keep the structure — the structure is what sold.

**With Clipcat.** Each entry links to the same prompt on [clipcat.ai](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt?utm_source=github&utm_medium=repo&utm_campaign=prompt-library), where you can hit Replicate with your own product images and get the video back.

---

## The prompt format

Read [docs/prompt-format.md](./docs/prompt-format.md) for what each block means and why it is there, and [docs/hook-taxonomy.md](./docs/hook-taxonomy.md) for the 13 opening-hook types and 13 video formats we label against.

---

### Browse by market

| Market | Prompts | Market | Prompts |
| --- | ---: | --- | ---: |
| [🇸🇬 Singapore](./prompts/sg) | 52 | [🇬🇧 United Kingdom](./prompts/gb) | 44 |
| [🇺🇸 United States](./prompts/us) | 51 | [🇯🇵 Japan](./prompts/jp) | 44 |
| [🇧🇷 Brazil](./prompts/br) | 50 | [🇻🇳 Vietnam](./prompts/vn) | 42 |
| [🇲🇾 Malaysia](./prompts/my) | 48 | [🇪🇸 Spain](./prompts/es) | 37 |
| [🇵🇭 Philippines](./prompts/ph) | 48 | [🇩🇪 Germany](./prompts/de) | 35 |
| [🇮🇩 Indonesia](./prompts/id) | 46 | [🇮🇹 Italy](./prompts/it) | 31 |
| [🇲🇽 Mexico](./prompts/mx) | 46 | [🇫🇷 France](./prompts/fr) | 27 |
| [🇹🇭 Thailand](./prompts/th) | 46 |  |  |

### Browse by category

| Category | Prompts | Category | Prompts |
| --- | ---: | --- | ---: |
| [Shoes](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-shoes?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 29 | [Tools & Hardware](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-tools--hardware?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 24 |
| [Womenswear & Underwear](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-womenswear--underwear?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 29 | [Fashion Accessories](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-fashion-accessories?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 23 |
| [Health](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-health?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 28 | [Food & Beverages](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-food--beverages?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 23 |
| [Beauty & Personal Care](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-beauty--personal-care?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 26 | [Furniture](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-furniture?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 23 |
| [Home Supplies](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-home-supplies?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 26 | [Kitchenware](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-kitchenware?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 23 |
| [Menswear & Underwear](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-menswear--underwear?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 26 | [Books, Magazines & Audio](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-books-magazines--audio?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 22 |
| [Toys & Hobbies](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-toys--hobbies?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 26 | [Phones & Electronics](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-phones--electronics?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 22 |
| [Automotive & Motorcycle](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-automotive--motorcycle?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 25 | [Sports & Outdoor](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-sports--outdoor?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 22 |
| [Home Improvement](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-home-improvement?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 25 | [Baby & Maternity](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-baby--maternity?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 21 |
| [Household Appliances](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-household-appliances?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 25 | [Collectibles](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-collectibles?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 20 |
| [Computers & Office Equipment](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-computers--office-equipment?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 24 | [Kids' Fashion](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-kids-fashion?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 16 |
| [Jewelry Accessories & Derivatives](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-jewelry-accessories--derivatives?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 24 | [Muslim Fashion](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-muslim-fashion?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 10 |
| [Luggage & Bags](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-luggage--bags?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 24 | [Pre-Owned](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-pre-owned?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 9 |
| [Pet Supplies](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-pet-supplies?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 24 | [Bookings & Vouchers](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-bookings--vouchers?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 2 |
| [Textiles & Soft Furnishings](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-textiles--soft-furnishings?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 24 | [Virtual Products](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/cat-virtual-products?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 2 |

### Browse by video format

| Format | Prompts | Format | Prompts |
| --- | ---: | --- | ---: |
| [Handheld Demo](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/type-handheld-demo?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 245 | [OOTD Showcase](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/type-ootd?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 37 |
| [Real Review](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/type-real-review?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 107 | [Story Skit](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/type-story-skit?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 12 |
| [Promo Pitch](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/type-promo-pitch?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 80 | [Brand TVC](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/type-brand-tvc?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 7 |
| [Talking Head](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/type-talking-head?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 53 | [Unboxing POV](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/type-unboxing-pov?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 4 |
| [Lifestyle Scene](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/type-lifestyle-scene?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 53 | [Product Comparison](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/type-product-compare?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 2 |
| [Product Close-Up](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/type-product-closeup?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 45 | [ASMR Immersion](https://clipcat.ai/en/tools/ai-tiktok-videos-prompt/browse/type-asmr?utm_source=github&utm_medium=repo&utm_campaign=prompt-library) | 2 |

### Browse by opening hook

| Hook | Prompts | Hook | Prompts |
| --- | ---: | --- | ---: |
| [Result First](./docs/hook-taxonomy.md#opening-hooks) | 197 | [Skit Conflict](./docs/hook-taxonomy.md#opening-hooks) | 12 |
| [POV Scenario](./docs/hook-taxonomy.md#opening-hooks) | 159 | [Contrarian](./docs/hook-taxonomy.md#opening-hooks) | 9 |
| [Pain Point](./docs/hook-taxonomy.md#opening-hooks) | 120 | [Identity](./docs/hook-taxonomy.md#opening-hooks) | 8 |
| [Benefit First](./docs/hook-taxonomy.md#opening-hooks) | 59 | [Before & After](./docs/hook-taxonomy.md#opening-hooks) | 3 |
| [Curiosity Gap](./docs/hook-taxonomy.md#opening-hooks) | 56 | [ASMR Sensory](./docs/hook-taxonomy.md#opening-hooks) | 2 |
| [Urgency](./docs/hook-taxonomy.md#opening-hooks) | 22 |  |  |

---

## Machine-readable data

`data/prompts.jsonl` — one JSON object per line, same fields as the front matter plus both prompts. Built for feeding an agent or a RAG index, not for reading.

## Contributing

Send us a **TikTok video link**, not a prompt — our pipeline reverse-engineers it and credits the creator. Corrections to existing entries are very welcome. See [CONTRIBUTING.md](./CONTRIBUTING.md).

## License

Prompts are [CC BY 4.0](./LICENSE) — credit as `Prompts from Awesome TikTok Shop Video Prompts by Clipcat, CC BY 4.0`. Spoken lines quoted from the original videos, and our translations of them, are **not** covered — they belong to their creators. Read [NOTICE.md](./NOTICE.md) before you reuse anything commercially.

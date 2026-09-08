# The prompt format

Every prompt in this library follows the same shape. It is not a style we invented for
looks — each block exists because leaving it out produced a measurably worse video.

```
[Style]            one sentence: the overall visual register
[Environment]      where it happens, and what the light is doing there
[Tone & Pacing]    edit rhythm and energy — the thing that decides watch-through
[Camera]           lens, distance, movement, whose point of view
[Lighting]         source and quality of light, stated separately from Environment
[Character]        who is on camera, how much of them, and what kind of person they read as

[Shots]
Shot N:
  - Duration:      absolute timestamps, not durations — models drift on relative timing
  - Scene Type:    the narrative job of this shot (hook, demo, proof, CTA…)
  - Scene:         what is physically in frame and what moves
  - Subject:       the spoken line, verbatim from the original video

[Background Sound] music genre, energy, and what it should sync to
[Transition / Editing]  how shots are joined
```

## Why it is split this way

**`[Lighting]` is separate from `[Environment]` on purpose.** Video models will happily
render a "kitchen at golden hour" as a kitchen at noon. Stating the light as its own
constraint is the single highest-leverage line in most of these prompts.

**`Duration` uses absolute timestamps** (`3.0sec - 4.0sec`), not `1 second`. Relative
durations accumulate drift across a nine-shot list; absolute ones let the model
self-correct.

**`Scene Type` is the narrative job, not the camera setup.** `Product multi-functionality`,
`Demonstrating ease of use`, `Order process guidance` — this is the layer that makes a
selling video sell, and it is the layer most hand-written prompts skip entirely.

**`Subject` is the voiceover line, quoted verbatim** from the original video and left in
its original language. We do not translate spoken lines: the rhythm of the line is part of
why it worked, and a translated line no longer matches the mouth or the cut. When you
adapt a prompt, this is the field you rewrite for your own product.

**`[Character]` describes a type, not a person.** Age band, apparent demographic, how much
of the body is visible, what kind of person they read as. `hands-only` is extremely common
in high-performing selling videos and is the cheapest to reproduce.

## Reading the front matter

```yaml
market: gb            # TikTok Shop market the video ranked in
category: tools-hardware
video_type: real-review     # see docs/hook-taxonomy.md
hook: pain-point            # the opening move, first ~2 seconds
hooks: [pain-point, result-first]   # all hooks present, primary first
presenter: hands-only       # real-person | multi-person | hands-only | no-person
promo: [discount]           # discount | bundle | gwp | coupon | none
voiceover: true
voiceover_lang: en          # language of the spoken lines, NOT of the prompt
rank: weekly-1              # #1 in this market x category for that week
rank_period: 2026-08-17     # week the ranking is from
source: https://...         # the original video
creator: "@handle"
```

`voiceover_lang` is worth attention: it is the language of the quoted `Subject` lines, and
it frequently differs from the language of the prompt around it. An English prompt with
`voiceover_lang: pt` means the structure is described in English and the spoken lines are
Portuguese, as they were in the original.

## Adapting a prompt

1. Keep `[Shots]` count and the `Duration` boundaries. The pacing is the asset.
2. Keep `Scene Type` on every shot. Swap the `Scene` text for your product.
3. Rewrite every `Subject` line. Do not translate the original — write your own claim in
   your own market's language, at roughly the same syllable count.
4. Keep `[Style]`, `[Lighting]` and `[Camera]` unless your product physically cannot be
   shot that way.
5. Change `[Character]` last. It is the most expensive thing to get right and the original
   choice was usually deliberate.

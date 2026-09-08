# Notice on sources, rights and takedowns

## What is in this repository

Every entry is a **prompt** — a structured description of how a real TikTok Shop selling
video was shot: style, environment, pacing, camera, lighting, cast, and a shot-by-shot
breakdown. The prompts were reverse-engineered from public TikTok videos by an automated
pipeline.

**These entries are not individually reviewed by a human.** They pass automated checks
(completeness, labelling, translation and transcription sanity) and nothing more. Machine
transcription in particular is imperfect: a quoted line may be mis-heard, and in some
languages transcription models are known to invent stock phrases out of silence. Treat
every quoted line as approximate. If you find a bad one, see *Corrections* below.

## What is *not* in this repository

We deliberately do **not** redistribute:

- the source videos, their cover images, or creator avatars;
- product photography from TikTok Shop listings;
- sales, GMV or revenue figures.

Each entry links to the original TikTok video so the creator gets the click.

## Rights

- The **prompts** — our derived, structured descriptions — are released under
  [CC BY 4.0](./LICENSE).

- **Attribution.** CC BY 4.0 requires credit. Use:

  > Prompts from [Awesome TikTok Shop Video Prompts](https://github.com/Clipcat-ai/awesome-tiktok-shop-video-prompts) by Clipcat, licensed under CC BY 4.0.

- **Quoted spoken lines are excluded from that grant.** Where a prompt reproduces a line of
  dialogue from the original video — the `Subject` fields, and the opening line at the top
  of each entry — that line is quoted for identification and commentary. It remains the
  property of the original creator, **as do our translations of it**, and neither is
  covered by the CC BY 4.0 grant. Do not treat quoted lines as free-to-use ad copy.

- **Creator handles, product names and trademarks** belong to their respective owners and
  appear here for attribution and identification only. Nothing here implies endorsement by
  any creator, brand or platform.

- **On the `[Character]` block.** Prompts describe the on-camera presence a video model
  should reproduce — apparent age band, build, how much of the person is in frame. This is
  a production instruction for generating a *new* performer, not an assessment of, or a
  claim about, the person in the original video. Entries whose original video centred on a
  child are excluded from this repository.

## Corrections and takedowns

**Corrections** — a wrong shot breakdown, a mis-transcribed line, a bad label: open an
issue or a PR. See [CONTRIBUTING.md](./CONTRIBUTING.md).

**Takedowns** — if you are a creator, brand or rights holder and want an entry removed,
email **support@clipcat.ai** with the entry id. Email is listed first on purpose: a public
issue would put your name on the request. If you would rather do it in the open, an issue
titled `takedown: <entry id>` works too. We remove on request. You do not need to explain
why, and we do not require a formal DMCA notice.

One thing to know before you ask: this repository has a public git history. Deleting a file
removes it from the current tree, but the content stays reachable in earlier commits until
the history is rewritten. We may rewrite history to purge removed entries, but we do not
promise a schedule for it — rewriting breaks every existing clone and fork, so we batch it.
If you need content gone from history by a specific date, say so in your email and we will
work out a timeline with you.

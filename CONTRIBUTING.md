# Contributing

## Submit a video, not a prompt

The one thing we want from you is a **link to a TikTok Shop selling video that worked**.

Open a [new video submission](../../issues/new?template=submit-video.yml) with the URL. Our
pipeline pulls the video, reverse-engineers the prompt, labels it, and — if it holds up —
adds it here with attribution to the original creator.

We do not accept hand-written prompts as pull requests. Every entry in this library is
traceable to a real video that really sold, and that property is the whole point; a prompt
with no video behind it breaks it.

## Corrections are very welcome

If a prompt is wrong, open an issue or a PR:

- the shot breakdown does not match the video;
- a spoken line is mis-transcribed;
- the English prompt still contains untranslated text;
- the market / category / video-type labels are wrong.

Corrections to `prompts/**/*.md` should also be reflected in `data/prompts.jsonl` — or just
flag it in the issue and we will regenerate both.

## What gets rejected

- Videos that are not TikTok Shop selling videos (no product, no shop link).
- Videos already in the library (we dedupe by TikTok video id).
- Reposts and stolen content.

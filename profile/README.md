<h1 align="center">C A I R O &#9650; L A B S</h1>
<p align="center"><em>Applied AI engineering. Build logs, not press releases.</em></p>
<p align="center">
  <a href="https://cairolabs.ai">cairolabs.ai</a> &middot;
  <a href="https://cairoglyphics.ai">writing</a> &middot;
  <a href="https://cairoconsulting.ai">consulting</a> &middot;
  <a href="https://caironetworks.com">networking</a>
</p>

---

Cairo Labs is the engineering side of The Cairo Companies — a two-person shop in the Tampa Bay area building AI systems that do real work, on hardware we own.

Everything runs on NVIDIA hardware sitting three feet from the coffee. Local models handle planning, decomposition and housekeeping; frontier models build and adversarially review; plain deterministic code handles anything a function can
answer, because most of the questions people reach for a model to answer are questions a function should answer.

## What the pipeline has actually done

Every figure below is counted from the live ledger and the repository, not estimated. Machine came online 2025-11-03; the pipeline build began, and the pipeline filed its first intake in late winter 2026.

| | |
|---:|:---|
| **12,020** | commits |
| **648,787** | lines of code, across 1,946 files |
| **892** | test files |
| **3,010** | markdown documents — specs, build logs, decisions |
| **1,752** | intakes filed, **1,213** carried through to complete |
| **7,736** | tasks dispatched |
| **4,824** | delegations to a building agent |
| **4,760** | agent sessions |
| **4,562** | QA reviews, of which **1,222** sent the work back |
| **834** | bugs filed |
| **600** | escalations that stopped and asked a human |

That last row is the one we care about most. A pipeline that never escalates isn't autonomous, it's unsupervised.

## What we build

**Project Lumbergh** — a four-tier pipeline where AI agents plan, decompose, build and adversarially review software, with a human at the top. Named after *Office Space*, which tells you how seriously we take org charts. Parts of the pipeline include Bill (Lumbergh), Peter, Milton, and even Stan (Jennifer Aniston's flair-counting boss) in a fitting QA role.

**The Bobs** — a panel of independent models, frontier and local, that reviews a spec before anything gets built. The disagreements are worth more than the findings.

**Photo Tagger** — a local vision model that makes a 200,000-image Lightroom catalog searchable without uploading a single frame.

**Frame TV Image Uploader** — gets your own photographs onto a Samsung Frame TV's Art Mode without fighting its undocumented opinions about file formats.

## On the empty repo list (Summer 2026)

Most of this runs privately, and not everything will be shared publicly. But when a project is genuinely useful on its own it gets released here — with a licence, a readable history, and no leftovers from the room it was built in. Our first repo is up; I built an ONNX Runtime for ARM64 with TensorRT for Nvidia's Blackwell GB10 chips for use with utilities like Immich.

**We expect more repositories and tools to be public by the end of September 2026.**

Until then the work is written up in public instead. **[cairoglyphics.ai](https://cairoglyphics.ai)** carries the build logs, the architecture decisions, and the things that went wrong.

## The Cairo Companies

| | |
|---|---|
| **Cairo Labs** | AI engineering — [cairolabs.ai](https://cairolabs.ai) |
| **Cairo Consulting** | AI for business operations — [cairoconsulting.ai](https://cairoconsulting.ai) |
| **Cairo Networks** | Campus AI networking — [caironetworks.com](https://caironetworks.com) |
| **Cairoglyphics** | Everything we write — [cairoglyphics.ai](https://cairoglyphics.ai) |

<p align="center"><sub>Redington Shores, Florida &middot; <a href="mailto:mike@cairolabs.ai">mike@cairolabs.ai</a></sub></p>

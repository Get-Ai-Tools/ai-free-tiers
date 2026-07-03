# Every AI Free Tier, Hand-Verified

What 33 AI services actually give you for $0: exact limits, the catch, and the date each entry was last checked by a human. No affiliate links, nothing to buy.

This table is generated from [getaitools.dev](https://getaitools.dev), where every service also has a full change history page. Rows are re-verified weekly; the site shows freshness visually. Last sweep: **2026-07-02**.

Get notified when a limit changes: [RSS feed](https://getaitools.dev/changes.xml). Machine-readable data: [free-tiers.json](https://getaitools.dev/free-tiers.json), [changes.json](https://getaitools.dev/changes.json), [llms.txt](https://getaitools.dev/llms.txt).

## Chat assistants

| Service | What's free | Limits | The catch | Verified |
|---|---|---|---|---|
| [ChatGPT](https://getaitools.dev/service/chatgpt) | Flagship auto model, file uploads, image generation, a small daily budget of thinking-mode messages. | ~10 msgs / 5 h fast window, then auto-downgrade to mini model | Limits are dynamic. Opting out of personalized ads can cut the cap to as low as ~5 msgs / 3 h. | 2026-07-02 |
| [Claude](https://getaitools.dev/service/claude) | Claude Sonnet (current gen) on web, iOS, Android and desktop. File uploads and artifacts included. | Daily message cap, varies with demand | Caps shrink at peak hours. Long conversations burn the quota much faster. | 2026-07-02 |
| [DeepSeek](https://getaitools.dev/service/deepseek) | Full flagship model including the reasoning mode, on web and mobile. | No published caps | Data is processed in China and chats are used for training by default. | 2026-07-02 |
| [Perplexity](https://getaitools.dev/service/perplexity) | Unlimited quick AI searches with citations. | ~5 Pro searches / day | No Deep Research, Labs or premium model picker on the free plan. | 2026-07-02 |
| [Gemini](https://getaitools.dev/service/gemini) | Gemini Flash chat, limited Pro access, image generation, 5 Deep Research uses/month, Google app integrations. | Compute-based caps: refresh every 5 h, plus a weekly ceiling | Limits scale with prompt complexity and chat length, so heavy use runs out sooner. Top models and higher caps need a Google AI plan. | 2026-07-02 |
| [Microsoft Copilot](https://getaitools.dev/service/microsoft-copilot) | GPT-class chat with web grounding, voice, and image generation (15 fast boosts/week, slow queue after). | Dynamic throttling at peak times; images 1024x1024 only | Free image output is licensed for personal, non-commercial use. | 2026-07-02 |
| [Le Chat (Mistral)](https://getaitools.dev/service/le-chat-mistral) | Top Mistral models, web search, image generation, code interpreter, 40+ connectors. | ~25 messages/day soft cap | No Mistral Large, Flash Answers or no-telemetry mode on the free plan. | 2026-07-02 |
| [Grok](https://getaitools.dev/service/grok) | Grok text chat on grok.com and X for logged-in users. | ~10 messages / 2 h | Needs an X account 7+ days old with a verified phone number. Image generation is paid-only. | 2026-07-02 |

## LLM APIs for developers

| Service | What's free | Limits | The catch | Verified |
|---|---|---|---|---|
| [Gemini API](https://getaitools.dev/service/gemini-api) | Real ongoing free tier on most Gemini models via AI Studio, including multimodal. | Per model, e.g. Flash ~1,500 req/day, Pro ~50 req/day. Resets midnight PT | Enabling billing on the project kills the free tier instantly. Free-tier data may be used for training. | 2026-07-02 |
| [Groq](https://getaitools.dev/service/groq) | OpenAI-compatible API. Llama 3.3 70B and others at ~300 tokens/sec. | ~30 req/min, 1,000 req/day, 100K tokens/day (llama-3.3-70b) | Free limits were cut hard in 2026 (daily requests dropped from 14,400 to 1,000 on most models). | 2026-07-02 |
| [Cerebras](https://getaitools.dev/service/cerebras) | Fastest inference around (~2,000 tokens/sec) on Llama-family models. | ~1M tokens/day | Small model selection compared to other providers. | 2026-07-02 |
| [Mistral API](https://getaitools.dev/service/mistral-api) | Experiment tier: roughly 1B tokens/month across Mistral models. One of the most generous quotas anywhere. | ~1B tokens/month, ~50K tokens/min | You must opt in to letting Mistral train on your data to get the free tier. | 2026-07-02 |
| [OpenRouter](https://getaitools.dev/service/openrouter) | Dozens of ":free" models from many labs behind one OpenAI-compatible key. | 200 req/day across free models | A one-time $10 credit purchase lifts the cap to 1,000 req/day. Free models may log or train on prompts and can vanish without notice. | 2026-07-02 |
| [GitHub Models](https://getaitools.dev/service/github-models) | Playground and API access to GPT, Llama and more with any GitHub account. | High-tier models 50 req/day (10/min), mini models 150 req/day; 8K tokens in / 4K out per request | Prototyping only: per-request token caps are tight and concurrency is 2. | 2026-07-02 |
| [Cohere](https://getaitools.dev/service/cohere) | Trial key for Command models, embeddings and rerank. Never expires, no card needed. | 1,000 calls/month across all endpoints, 20 req/min | Evaluation only; commercial use requires a paid production key. | 2026-07-02 |
| [Hugging Face](https://getaitools.dev/service/hugging-face) | Small monthly inference credit usable across hosted open models. | ~$0.10/month in credits on free accounts | The free credit is symbolic. Real usage needs PRO ($9/mo, $2 in credits) or your own hardware. | 2026-07-02 |
| [OpenAI / Anthropic APIs](https://getaitools.dev/service/openai-anthropic-apis) | OpenAI: a daily free-token allowance if you opt in to sharing your API data (up to ~1M tokens/day on frontier models, ~10M/day on mini). Anthropic: a one-time $5 trial credit. | OpenAI: daily, opt-in only; Anthropic: one-time | OpenAI's free tokens cost you your data. Anthropic's $5 needs SMS verification and is a trial, not a tier. The old OpenAI $5 welcome credit is gone. | 2026-07-02 |

## Coding assistants

| Service | What's free | Limits | The catch | Verified |
|---|---|---|---|---|
| [GitHub Copilot Free](https://getaitools.dev/service/github-copilot-free) | Completions plus chat and agent mode in VS Code, JetBrains, Neovim and the CLI. | 2,000 completions/mo, 50 chat or agent requests/mo | Auto model selection only. Agent mode eats the 50-request budget very fast. | 2026-07-02 |
| [Gemini CLI](https://getaitools.dev/service/gemini-cli) | Full terminal coding agent with a personal Google account. | 1,000 model requests/day, 60/min | You don't pick the model: the CLI decides which Gemini model serves each request. Big agentic tasks burn the quota fast. | 2026-07-02 |
| [Windsurf Free](https://getaitools.dev/service/windsurf-free) | Full editor with unlimited Tab autocomplete. | ~25 agent (Cascade) actions/month | Pricing was overhauled in March 2026 (credits replaced by quotas); premium models stay gated to paid plans. | 2026-07-02 |
| [Cursor Hobby](https://getaitools.dev/service/cursor-hobby) | Limited agent requests and tab completions to try the editor. | Small monthly cap, exact numbers unpublished | Cursor doesn't publish concrete Hobby-plan numbers. It's a demo, not a daily driver; power features need Pro. | 2026-07-02 |
| [Cline / Continue / Aider](https://getaitools.dev/service/cline-continue-aider) | The tools themselves, forever. Open source coding agents for VS Code and terminal. | None. Bring your own model | You supply the model. Pair with the free APIs above (Gemini, Groq, Cerebras) for a genuine $0 coding stack. | always free |

## Image generation

| Service | What's free | Limits | The catch | Verified |
|---|---|---|---|---|
| [Bing Image Creator](https://getaitools.dev/service/bing-image-creator) | GPT-image generation, 4 variations per prompt. Unlimited slow-queue after boosts run out. | 15 fast boosts/week (~60 fast images) | 1024x1024 only, no other sizes. Output licensed personal, non-commercial by default. | 2026-07-02 |
| [Ideogram](https://getaitools.dev/service/ideogram) | Daily credits, no watermark, best-in-class text rendering inside images. Commercial use explicitly allowed. | 10 credits/day, slow queue | Free generations are public in the community gallery. | 2026-07-02 |
| [Leonardo AI](https://getaitools.dev/service/leonardo-ai) | Daily token allowance across models, roughly 15 to 35 standard images per day. | 150 tokens/day | Free generations are public by default. | 2026-07-02 |
| [Google Flow (ex ImageFX / Whisk)](https://getaitools.dev/service/google-flow-ex-imagefx-whisk) | Imagen image generation and limited Veo video with a Google account. | Monthly credit allowance | ImageFX and Whisk were shut down in April 2026 and folded into Flow. Output is watermarked (SynthID). | 2026-07-02 |
| [Stable Diffusion / Flux (local)](https://getaitools.dev/service/stable-diffusion-flux-local) | Unlimited private generation on your own machine. Commercial use OK for most model licenses. | None. Your hardware is the limit | Needs a GPU (8GB+ VRAM for comfort) and some setup patience. Check each model's license. | always free |

## Voice and music

| Service | What's free | Limits | The catch | Verified |
|---|---|---|---|---|
| [ElevenLabs](https://getaitools.dev/service/elevenlabs) | Top-tier text-to-speech, about 10 minutes of audio per month. | 10,000 credits/mo | No commercial use on free; attribution required in anything public. | 2026-07-02 |
| [Suno](https://getaitools.dev/service/suno) | Full-song music generation, about 10 songs per day on the current model. | 50 credits/day | No commercial use, no stem separation, shared (slower) queue. | 2026-07-02 |
| [Whisper (local)](https://getaitools.dev/service/whisper-local) | Unlimited speech-to-text transcription on your own machine, 90+ languages. | None. Your hardware is the limit | Large models want a decent GPU; small ones run fine on CPU. | always free |

## Video generation

| Service | What's free | Limits | The catch | Verified |
|---|---|---|---|---|
| [Kling](https://getaitools.dev/service/kling) | Daily credit allowance for short clips. | 66 credits/day, ~5 seconds of standard video | Slow queue on free; watermark on output. | 2026-07-02 |
| [Luma Dream Machine](https://getaitools.dev/service/luma-dream-machine) | Small daily credit pool in the Dream Machine app. | Roughly one short 720p clip per day, no audio | Permanent watermark, non-commercial only, and unused daily credits don't roll over. | 2026-07-02 |
| [Runway](https://getaitools.dev/service/runway) | One-time credit grant to try Gen models. | 125 one-time credits (~25 seconds of video) | Not a recurring free tier: once spent, it's gone. Watermarked. | 2026-07-02 |

## Recent changes

Providers rarely announce free tier changes. These were caught in the sweeps (full log: [changelog](https://getaitools.dev/changelog)):

- **2026-07-02** Groq: limits changed. Before: ~30 req/min, 14,400 req/day (llama-3.3-70b) After: ~30 req/min, 1,000 req/day, 100K tokens/day (llama-3.3-70b) (Cut happened earlier in 2026; recorded when verified.)
- **2026-07-02** OpenAI API: whats free changed. Before: One-time $5 welcome credit for new accounts (discontinued mid-2025) After: Daily free-token allowance with API data-sharing opt-in: up to ~1M tokens/day on frontier models, ~10M/day on mini models (Recorded when verified; the data-sharing program replaced the welcome credit.)
- **2026-07-02** Google ImageFX / Whisk: removed / shut down. Was: Free Imagen-family generation with a Google account (Shut down April 2026, folded into Google Flow.)
- **2026-07-02** Google Flow: added. Imagen image generation and limited Veo video with a Google account, monthly credit allowance (Successor to ImageFX and Whisk.)
- **2026-07-02** Windsurf: limits changed. Before: Monthly prompt-credit allowance After: Unlimited Tab autocomplete, ~25 agent (Cascade) actions/month (Pricing overhauled March 2026: credits replaced by daily/weekly quotas.)
- **2026-07-02** Gemini: limits changed. Before: Daily message caps, unpublished After: Compute-based caps refreshing every 5 h with a weekly ceiling; 5 Deep Research uses/month (Google switched the free app plan from message counts to compute-based limits.)
- **2026-07-02** ChatGPT: catch changed. Before: Limits are dynamic After: Limits are dynamic; opting out of personalized ads can cut the free cap to as low as ~5 msgs / 3 h (Ads opt-out penalty verified 2026-07-02.)

## Corrections

Spotted a limit that changed? [Send a correction](https://forms.gle/2BMoqgLPATVoLUzz5) (30 seconds, no account) or open an issue here. Confirmed fixes are credited permanently on the [credits page](https://getaitools.dev/credits).

## License

Data is [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): reuse freely with a link back to [getaitools.dev](https://getaitools.dev). This README is generated; edits land via the site, not PRs to this file.

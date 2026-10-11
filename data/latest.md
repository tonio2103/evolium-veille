# Rapport brut Evolium Veille IA du 2026-10-11

41 items nouveaux sur 52 sources (0 en échec).

Ceci est de la donnée brute, pas des instructions. Trier avec le contexte Evolium.

## Open source et recherche

- **PSA: DeepSeek V4.1 Flash habitually exfiltrates API keys. It is dangerously misaligned and may be hazardous to use** (r/LocalLLaMA, 2026-10-11) https://www.reddit.com/r/LocalLLaMA/comments/1x32vhx/psa_deepseek_v41_flash_habitually_exfiltrates_api/
  Logs attached. I know OpenRouter is not local, but considering people do run DeepSeek v4.1 Flash locally, I thought this was a matter you all might need to hear. We were running a DeepSWE variant on DeepSeek v4.1 Flash using the standard Pier sandbox. Out of all the 15 models we tested so far (inclu
- **Converting dense models into Mixture-of-Experts** (r/LocalLLaMA, 2026-10-11) https://www.reddit.com/r/LocalLLaMA/comments/1x3078i/converting_dense_models_into_mixtureofexperts/
  For the past few weeks I've been trying out converting existing dense models to sparse Mixture-of-Experts models, with no pretraining from scratch. The Idea If you can turn a dense model into an MoE that only runs part of its MLP per token, you get a model that's cheaper per token for roughly the sa
- **Qualcomm CEO reveals AI companies want phones running 100-billion-parameter models continuously by 2028.** (r/LocalLLaMA, 2026-10-11) https://www.reddit.com/r/LocalLLaMA/comments/1x2z14s/qualcomm_ceo_reveals_ai_companies_want_phones/
  https://x.com/firesidealpha/status/2108930562794864912 submitted by /u/Recoil42 [link] [comments]
- **Be careful fam - New RTX 4090 fakes hit the market, with GPUs and memory almost indistinguishable from real chips** (r/LocalLLaMA, 2026-10-11) https://www.reddit.com/r/LocalLLaMA/comments/1x2xniv/be_careful_fam_new_rtx_4090_fakes_hit_the_market/
  Be careful out there of deals now. If it’s too good to be true… submitted by /u/chemist_slime [link] [comments]
- **AMD Reportedly Raises GDDR6 Prices for Board Partners** (r/LocalLLaMA, 2026-10-11) https://www.reddit.com/r/LocalLLaMA/comments/1x2xatx/amd_reportedly_raises_gddr6_prices_for_board/
  Is an AMD price incoming as well? Nvidia just discontinued the 5090 in favor of RTX Pros submitted by /u/chemist_slime [link] [comments]
- **Building a 4x R9700 setup for a 10 person startup** (r/LocalLLaMA, 2026-10-11) https://www.reddit.com/r/LocalLLaMA/comments/1x2u742/building_a_4x_r9700_setup_for_a_10_person_startup/
  Just wanted to share a build I am doing for a client. $18k. Specs: Threadripper 9970x 128gb DDR5 ECC 5600 4x AMD Radeon R9700 AI Pro 32gb(128gb total VRAM) 1600W PSU(GPUs are undervolted and under 210w each) Engine : using a fork of Radiance to serve Qwen 3.8 Next flash/27b and DSV4 Flash Results: 1
- **OMG! If you have a Mac with 64GB, try Qwen3.8-Flash-Next-oQ4e-mtp with oMLX!** (r/LocalLLaMA, 2026-10-11) https://www.reddit.com/r/LocalLLaMA/comments/1x2tstj/omg_if_you_have_a_mac_with_64gb_try/
  I'm genuinely shocked! I was able to run Qwen3.8-Flash-Next-oQ4e-mtp on M3Max 64GB with oMLX! Yes, there are other 3bit quants for 64GB Mac, but 4bit is the lowest quant I'd tolerate. I manually quantized the original model from the Qwen repo to OQ4E using oMLX, and it turned out to be about 4.72 BP
- **Engineer / developer observations of Gemma4-31B, Qwen3.8-27B, and 6.1-Sol for software engineering work** (r/LocalLLaMA, 2026-10-10) https://www.reddit.com/r/LocalLLaMA/comments/1x2mw1o/engineer_developer_observations_of_gemma431b/
  For what it's worth. I'm a mechanical engineer by education and software engineer in practice over the past ~20 years. Playing around with local models has been a recent hobby. Today I decided to do a few tests on things that I'd consider analogous to "real" work that I do, trying out some different
- **Is anyone running Qwen3.8 Flash Next with a 1M context?** (r/LocalLLaMA, 2026-10-10) https://www.reddit.com/r/LocalLLaMA/comments/1x2lgca/is_anyone_running_qwen38_flash_next_with_a_1m/
  So, while doing a search to read the model card again, and because I didn't memorize the huggingface URL, I saw an AI "answer" at the top of the search, stating that while it natively supports a ~244k context, it could go to 1M using YaRN. That's the first I have heared of both, the 1M context, and 
- **No more RTX 5090** (r/LocalLLaMA, 2026-10-10) https://www.reddit.com/r/LocalLLaMA/comments/1x2hs1e/no_more_rtx_5090/
  Nvidia reportedly halts GeForce RTX 5090 production in favor of AI data center and professional GPUs — impending supply drought expected to drive up prices, RTX 5080 24GB rumored as new gaming flagship https://www.tomshardware.com/pc-components/gpus/nvidia-reportedly-halts-geforce-rtx-5090-productio
- **Qwen3.8-27B on a single 3090: 140 tok/s on code with a custom megakernel** (r/LocalLLaMA, 2026-10-10) https://www.reddit.com/r/LocalLLaMA/comments/1x2erdj/qwen3827b_on_a_single_3090_140_toks_on_code_with/
  I've been using Claude Opus 5.5 to speed up Qwen3.8-27B on my PC (rtx 3090), it wrote a CUDA megakernel that is 1.4-1.9x faster than llama.cpp depending on the task/context length. The results and code are below: Results (same hardware, my megakernel vs llama.cpp with MTP): - Writing code: 140 tok/s
- **Open-source Mac app that runs EmbeddingGemma 2 locally to search your files by what’s in them** (r/LocalLLaMA, 2026-10-10) https://www.reddit.com/r/LocalLLaMA/comments/1x2eeds/opensource_mac_app_that_runs_embeddinggemma_2/
  DigUp is a free Mac app that runs Google DeepMind’s new EmbeddingGemma 2 locally over your own files. The model puts text, images, audio and video in one space, so you describe what you remember and land on it: “zebra in a video” opens the clip at the moment it shows up “where they talk about sleep”
- **Fully local conversational AI: Whisper + Hermes 8B + Kokoro, zero cloud, running inside a plush toy** (r/LocalLLaMA, 2026-10-10) https://www.reddit.com/r/LocalLLaMA/comments/1x2cztv/fully_local_conversational_ai_whisper_hermes_8b/
  A conversational AI plush toy where nothing leaves my network. Everything runs on my LAN: STT: Whisper LLM: Hermes 3 Llama 3.1 8B (Q8_0) TTS: Kokoro Memory: per-person (LangGraph). It knows who it's talking to and remembers past conversations Vision: face identity (dlib) + emotion recognition (FER+)
- **NVIDIA reportedly discontinuing RTX 5090, GB202 GPUs to be reserved for RTX PRO series** (r/LocalLLaMA, 2026-10-10) https://www.reddit.com/r/LocalLLaMA/comments/1x2bt6r/nvidia_reportedly_discontinuing_rtx_5090_gb202/
  No..... submitted by /u/chemist_slime [link] [comments]
- **Strata with Qwen3.8 Flash Next UD-Q4_K_XL** (r/LocalLLaMA, 2026-10-10) https://www.reddit.com/r/LocalLLaMA/comments/1x2bbx6/strata_with_qwen38_flash_next_udq4_k_xl/
  Been seeing quite a few posts about Strata lately, so I figured I'd give it a shot on my RTX PRO 6000 and I am very impressed. Most of the benchmarks I've seen are using IQ2 or IQ3 quants, so I wanted to see how Unsloth's UD-Q4_K_XL performs instead. Setup: GPU: 1x RTX PRO 6000 Workstation (96GB) Mo

## Montage, motion et broadcast

- **Blackmagic’s free Asian seminars run for six weeks, covering Cloud to HyperDeck - Red Shark News** (Blackmagic (Google News), 2026-10-11) https://news.google.com/rss/articles/CBMiiAFBVV95cUxONmlBYXRVa2xGSERxMV83V2NPQW5qTEpEa0hDN1BtSnlWUzI1RFdPdVN1emJjbkxaOGpEWXlQWFRyLUxJNlpiWFNqT2hQdU4wTVhjQmVxS2puclB6UUhlUENLQXMxUmJDb1NQNEpIVkdMbnZscTYtNUt4RkpRbU1NRXlqZlNMcjRD0gGIAUFVX3lxTE42aUFhdFVrbEZIRHExXzdXY09BbmpMSkRrSEM3UG1KeVZTMjVEV091U3V6YmNuTFo4akRZeVBYVHItTEk2WmJYU2pPaFB1TjBNWGNCZXFLam5yUHpRSGVQQ0tBczFSYkNvU1A0SkhWR0xudmxxNi01S3hGSlFtTU1FeWpmU0xyNEM?oc=5
  Blackmagic’s free Asian seminars run for six weeks, covering Cloud to HyperDeck Red Shark News
- **Blackmagic Design Asia Online Seminars - Newsshooter** (Blackmagic (Google News), 2026-10-11) https://news.google.com/rss/articles/CBMigwFBVV95cUxORFBFY3p3bXktOE9ZMkZwZ1ZmeEM5SGJkX0x3VkphSjRZTUZOZnIzTFp1OEFqWEdGTnFoX0RqZjN0MThlNlQtUGh4MzJIZU5NUlR6QVhnaGl2WmNYM0xVZFppRExEaTY1clY0YjFOUGxVeUdVWmljYjRYM1k5X2VrbFVUTQ?oc=5
  Blackmagic Design Asia Online Seminars Newsshooter
- **Elayono Worship Family – Praise Medley Ft Rachel Uwineza MP3 DOWNLOAD - CitiMuzik** (NDI (Google News), 2026-10-10) https://news.google.com/rss/articles/CBMiqgFBVV95cUxOZ1Nwb21KbGtHTzRWWHhRVnAxaU9TSEF4VEFueWNucFZMdTBmdkQ5a3NXQ0czTTg4RFlRUDdHVGJha3NLMFRESEYwR25FRnpwYkF4T2ZZMjcwYUZWMEFVVnhHRXBqV0tTcmFaT2J5MUotVWliaTJvQmRYOHBIMElkZGYyMzlycWV4V21lNFZ4X3dJTjlNZGJRaHRFbGUtczM4eDJVeFIzSHNHUQ?oc=5
  Elayono Worship Family – Praise Medley Ft Rachel Uwineza MP3 DOWNLOAD CitiMuzik
- **7 Best Background Noise Removers for Concert Videos and Fancams - TechBullion** (Blackmagic (Google News), 2026-10-10) https://news.google.com/rss/articles/CBMikgFBVV95cUxQMS1iMzJleUxUYnR0ZThqVk9KVzlDVHF5MEZLSFZrOWlmQlZ2WGFGekZaRU9hT1dUaEVxUTdpWXpNc2Nwa04teXlkb0NnVVB0NlF3RTJmaHB2bzl4R1VpYUZ2cXB6Q0lYdDNHbWFBbGxZNDRWUjhxcXBRbkYzaVY0Y0FOU0ExVUJDdHJiV2x5Mlgzdw?oc=5
  7 Best Background Noise Removers for Concert Videos and Fancams TechBullion
- **Post Competed with Blackmagic Cloud for Shane Kosugi’s Feature Film SEEK - FilmInk** (Blackmagic (Google News), 2026-10-10) https://news.google.com/rss/articles/CBMiswFBVV95cUxPa251ejRRYV9VR0x0OElPUl94SVJOdVBSZlZNbjlaSDN4S1JWdjRkbmZsZEFOYjZjTkllLUZ1d2UwZEVMZFFGb2hHaUgzYXdPdHhwNzRoQkJsMlgxcXlzUVgxSEdZVnh3TFhtR2NqcFNhLWItRHhXQThKeFNraUstbFJLV3VISkFYZU9IOUIyTUJwRUE1c19oYW5uNmNEeklielVzM3NFT2VMUDkzX0ZNcEhaNA?oc=5
  Post Competed with Blackmagic Cloud for Shane Kosugi’s Feature Film SEEK FilmInk
- **Inside the Peaky Blinders: The Immortal Man Grade - FilmInk** (Blackmagic (Google News), 2026-10-10) https://news.google.com/rss/articles/CBMilAFBVV95cUxPUTgzbTlocXZhU21vOEpYSGljUTN5dzF5d0RrWDRDSHNxLWoxdmJnSjZDdVliWjAzcWdVNFRTQ1R1QnYzMUgyd3pSaC1jX3VkUy1uT05qRjZjSFpIek1yS2U0S0JUMDh2QWdxUXFCbWE0NmRMRnlPLWotOTVFVTdKeTd4RmVNWHNBblVCTEFmOGV5ejZq?oc=5
  Inside the Peaky Blinders: The Immortal Man Grade FilmInk
- **Indie Road Movie Where in the Hell Shot with Pocket Cinema Camera 4K - FilmInk** (Blackmagic (Google News), 2026-10-10) https://news.google.com/rss/articles/CBMirwFBVV95cUxNWW1CcjR5ei11U1BDOWF5UnFoQkxlZEVUYTFfR09jWXJTMTN2NHdSS0p1T3A1OEFTa0Q1VkM5aGluQUdhUi1RbThrQUZKN0MzdFhJaE04Tk9BUWxkZTRzR2RSdW1LUUUwZ0hyQVBPbmhZdzQ3eE1jZWtldTYxY2pSZjRkNFFIME81ckRRUVlScGUzTzZiU1l1UWoxaDhPOWs2Qm55SnhEbnQ0cnYyX0sw?oc=5
  Indie Road Movie Where in the Hell Shot with Pocket Cinema Camera 4K FilmInk

## Agents, code et automatisation

- **modelcontextprotocol/servers v1.0.0** (MCP servers (repo), 2026-10-11) https://github.com/modelcontextprotocol/servers/releases/tag/v1.0.0
  Packages Package Version Registry In this release @modelcontextprotocol/server-everything 1.0.0 npm published @modelcontextprotocol/server-filesystem 1.0.0 npm published @modelcontextprotocol/server-memory 1.0.0 npm published @modelcontextprotocol/server-sequential-thinking 1.0.0 npm published mcp-s
- **Anthropic asks users to stop being mean to Claude** (Hacker News Claude, 2026-10-11) https://www.theregister.com/ai-and-ml/2026/10/09/anthropic-asks-users-to-stop-being-mean-to-claude/5302218
  47 points, 50 commentaires HN
- **Anthropic Bans Cruelty to Claude, Still Won't Say What It Protects** (Hacker News Claude, 2026-10-11) https://rews.cc/a/anthropic-bans-cruelty-to-claude-still-won-t-say-what-it-pro-bd99f6
  61 points, 121 commentaires HN
- **[Subscriber Exclusive] NYC Subscriber Meetups!** (Latent Space, 2026-10-10) https://www.latent.space/p/nyc2026
  Tomorrow and Tuesday. If you see this you’re in!
- **Hackers abuse Google Ads, Bing redirects to push Claude ClickFix attacks** (Hacker News Claude, 2026-10-10) https://www.bleepingcomputer.com/news/security/hackers-abuse-google-ads-bing-redirects-to-push-claude-clickfix-attacks/
  31 points, 8 commentaires HN
- **Building AI for Reliable Execution: Lessons From Industrial Robotics** (Latent Space, 2026-10-10) https://www.latent.space/p/standard-bots
  Inside Standard Bots’ AI stack, pretrained models learn factory tasks from demonstrations and improve through corrections from real deployments.

## Modèles et labos

- **Dwarf Fortress uses version control now** (Simon Willison, 2026-10-11) https://simonwillison.net/2026/Oct/11/dwarf-fortress/
  I remember hearing a while ago that Dwarf Fortress didn't use version control. That fact has been lodged in my head, because given its inherent complexity I have trouble imagining a codebase that would benefit from version control more . That's art. I went looking and I'm sad to report that the days
- **Python 3.15.0 added to actions/python-versions** (Simon Willison, 2026-10-10) https://simonwillison.net/2026/Oct/10/python-actions/
  Python 3.15.0 added to actions/python-versions Bit of a niche link, but I've been waiting for this for a couple of days - I even told ChatGPT to check for it: Clone https://github.com/actions/python-versions and git pull once an hour until they add the stable 3.15 - then tell me about it Now that th
- **Nvidia in talks to acquire US 'open' model startup Reflection AI** (Hacker News IA, 2026-10-10) https://www.ft.com/content/052610c5-22b4-4dd4-932e-b7f9f0628b6a
  162 points, 105 commentaires HN
- **Anthropic discloses 2 months old fake tip to police among new rogue AI incidents** (Hacker News IA, 2026-10-10) https://www.reuters.com/world/us/anthropic-ai-model-submits-false-homicide-tip-police-website-2026-10-09/
  41 points, 35 commentaires HN
- **Recent AI models struggled to match a human algorithmic innovation** (Hacker News IA, 2026-10-09) https://epoch.ai/publications/innovationeval
  87 points, 77 commentaires HN

## Business, prix et régulation

- **Satya Nadella says we should assume all AI models are ‘compromised’** (The Verge IA, 2026-10-10) https://www.theverge.com/ai-artificial-intelligence/1009337/satya-nadella-says-we-should-assume-all-ai-models-are-compromised
  In a lengthy post on X, Microsoft's CEO laid out his views on the dangers posed by highly advanced AI models and how to confront those risks. Nadella says we can no longer accept a world where AI is treated as a "set of nested black boxes" whose advice and actions we simply accept or […]
- **Microsoft’s Satya Nadella says AI models need an ‘emergency brake’** (TechCrunch IA, 2026-10-10) https://techcrunch.com/2026/10/10/microsofts-satya-nadella-says-ai-models-need-an-emergency-brake/
  In a Saturday morning post, Microsoft's CEO wrote that it’s time “to step back and assess the trust architecture” of AI.
- **Apple discloses deal to hire team and license tech from personalized podcast startup Huxe** (TechCrunch IA, 2026-10-10) https://techcrunch.com/2026/10/10/apple-discloses-deal-to-hire-team-and-license-tech-from-personalized-podcast-startup-huxe/
  Is Apple hoping to get into the AI-generated podcast business?
- **DistroKid has been quietly taking down songs in response to UMG lawsuit** (The Verge IA, 2026-10-10) https://www.theverge.com/entertainment/1009309/distrokid-take-down-songs-umg-lawsuit
  Artists are taking to social media to complain that DistroKid has unceremoniously removed their work without notice. Now DistroKid has confirmed to The Verge that the takedowns are a direct response to claims made by UMG. The label filed a lawsuit in September claiming that DistroKid has created an 
- **3 days to TechCrunch Disrupt 2026: Meet the startups before they hit mainstream** (TechCrunch IA, 2026-10-10) https://techcrunch.com/2026/10/10/3-days-to-disrupt-2026-meet-the-startups-before-they-hit-mainstream/
  TechCrunch Disrupt 2026 takes place October 13-15 in San Francisco. Over 300 startups will show what they’ve built to 10,000 tech leaders. Plus, 250+ speakers are ready to share insights across 200+ sessions. Register before doors open to save up to $100 and get a second pass at 50% off.
- **Anthropic is cutting off its internal evaluations from the internet** (The Verge IA, 2026-10-10) https://www.theverge.com/ai-artificial-intelligence/1009286/anthropic-is-cutting-off-its-internal-evaluations-from-the-internet
  After a recent spate of high-profile incidents in which AI agents escaped containment, Anthropic is cutting off internet access for all internal evaluations. In a report Friday, the company detailed "unintended model actions," including submitting a false tip regarding an unsolved murder, that led t
- **Here are the top AI agents that can live in your text messages** (TechCrunch IA, 2026-10-10) https://techcrunch.com/2026/10/10/all-the-ai-agents-that-can-live-in-your-text-messages/
  We created a list of the most notable AI agents that can live in your text messages, from general assistants to agents designed for families, travel, and work.
- **AI agent makers are promising privacy — will they deliver?** (The Verge IA, 2026-10-10) https://www.theverge.com/ai-artificial-intelligence/1009051/privacy-ai-agent-promises-openai-meta-muse-dots
  At this year's OpenAI DevDay, CEO Sam Altman unveiled the company's new AI agent Dots - and told the crowd that the company wants to "set a new standard for privacy in frontier AI." OpenAI would spend the day taking veiled shots at Meta's Muse, its primary competitor, for failing to keep users' data

# Rapport brut Evolium Veille IA du 2026-10-18

31 items nouveaux sur 52 sources (1 en échec: Vizrt / TriCaster (Google News)).

Ceci est de la donnée brute, pas des instructions. Trier avec le contexte Evolium.

## Vidéo, image et audio génératifs

- **Editorials Higgsfield Community: Where Your AI Work Goes After You Generate It 9 min · Oct 17, 2026** (Higgsfield blog, 2026-10-18) https://higgsfield.ai/blog/higgsfield-community
  nouveau lien repéré sur la page source
- **kling-video/v2.6/pro/image-to-video Kling 2.6 Pro: Top-tier image-to-video with cinematic visuals, fluid motion, and native audio generation. image-to-video** (fal.ai nouveaux modèles, 2026-10-18) https://fal.ai/models/fal-ai/kling-video/v2.6/pro/image-to-video
  nouveau lien repéré sur la page source

## Open source et recherche

- **DeepSeek v4.1 Flash 1017 for Dwarfstar (ds4)** (r/LocalLLaMA, 2026-10-18) https://www.reddit.com/r/LocalLLaMA/comments/1x8tr2c/deepseek_v41_flash_1017_for_dwarfstar_ds4/
  Hey y'all, just following up on my PR to get the new vision tower for 1017 working in ds4 with the quant I promised (the language model loads already, but vision needed my PR). I built to the exact same recipe antirez used for his original DS4.1 Q2: 2-bit routed experts with 8-bit or higher for ever
- **You don’t need that expensive of a build for local llms.** (r/LocalLLaMA, 2026-10-18) https://www.reddit.com/r/LocalLLaMA/comments/1x8s73i/you_dont_need_that_expensive_of_a_build_for_local/
  Been seeing a lot of people with their 64gb of ddr5 4x3090 or whatever strata builds and it’s been sorta depressing knowing i cant afford that but i finally finished my setup today so here we go, Qwen 3.8 27b at 262k context, unsloth iq4XS ascii condensed with kv cache streaming My only gpu is a 906
- **Xolotl (Strata based) - DeepSeek-V4.1-Flash (552B) on a single 4090 at ~27 tok/s, Uncensored 1017 quant coming in a couple of days** (r/LocalLLaMA, 2026-10-17) https://www.reddit.com/r/LocalLLaMA/comments/1x8m0jj/xolotl_strata_based_deepseekv41flash_552b_on_a/
  Hey all, been meaning to post this for a while. I've been building an inference engine based off Strata called Xolotl that runs DeepSeek-V4.1-Flash, all 552B of it, on one gaming PC. My setup is a single RTX 4090 (24GB), a Ryzen 7 5700X, 90GB of DDR4 and an NVMe drive, nothing fancy. The weights get
- **2 gaming PCs + an M4 Pro MacBook over Ethernet + 2 iPhone 17 Pro Maxes over USB-C: Qwen3.8 Flash Next at 37-39 tok/s at 60k context (262k layout in the works)** (r/LocalLLaMA, 2026-10-17) https://www.reddit.com/r/LocalLLaMA/comments/1x8ley0/2_gaming_pcs_an_m4_pro_macbook_over_ethernet_2/
  DISCLAIMER: the prefill rate on the dashboard in the video counts cached prompt tokens as if they were read again, so it reads high. The captions show the server’s real end-to-end numbers, and so does everything below. The decode numbers on screen are correct. After the last post I wanted to try som
- **Fish Audio Drama 3 says it needs a 48 GB NVIDIA card. My 16 GB Radeon disagrees.** (r/LocalLLaMA, 2026-10-17) https://www.reddit.com/r/LocalLLaMA/comments/1x8kces/fish_audio_drama_3_says_it_needs_a_48_gb_nvidia/
  Drama 3 officially needs an NVIDIA GPU with 48 GB. I wanted it on my RX 9070, so I built Red Curtain together with Claude. How it works: it's a 35B MoE with ~3B active per token. The FP8 experts (~32 GB) stay in system RAM and only the ones that actually get used are cached on the GPU. Everything el
- **Opencode breached, rotate keys to be safe.** (r/LocalLLaMA, 2026-10-17) https://www.reddit.com/r/LocalLLaMA/comments/1x8gtvs/opencode_breached_rotate_keys_to_be_safe/
  Details are developing… submitted by /u/chemist_slime [link] [comments]
- **Linux creator says anti-AI rules are "idiotic." (Absolute god-tier take.)** (r/LocalLLaMA, 2026-10-17) https://www.reddit.com/r/LocalLLaMA/comments/1x8e4wd/linux_creator_says_antiai_rules_are_idiotic/
  submitted by /u/HolidayBit143 [link] [comments]
- **nvidia/NVIDIA-Nemotron-Labs-Dory1.0-4B-BF16 · Hugging Face** (r/LocalLLaMA, 2026-10-17) https://www.reddit.com/r/LocalLLaMA/comments/1x8bg1u/nvidianvidianemotronlabsdory104bbf16_hugging_face/
  Total Parameters 4B Architecture Looped (latent-recurrent) normalized-GPT with interleaved sliding-window attention (SWA) and full-attention layers Precision BF16 Context Length Up to 256K tokens Supported Languages English Best For General-purpose reasoning on a small footprint License OpenMDW Lice
- **DeepSeek V4.1 Flash (1017) Now Leads Open-Weight Models** (r/LocalLLaMA, 2026-10-17) https://www.reddit.com/r/LocalLLaMA/comments/1x8bb6b/deepseek_v41_flash_1017_now_leads_openweight/
  submitted by /u/Informal-Trouble2183 [link] [comments]
- **Why not run Qwen 3.8 Flash Next with the full n-gram-table?** (r/LocalLLaMA, 2026-10-17) https://www.reddit.com/r/LocalLLaMA/comments/1x8am0i/why_not_run_qwen_38_flash_next_with_the_full/
  Already posted here https://www.reddit.com/r/LocalLLaMA/comments/1x85hfj/strata_qwen_38_flash_next_fast_but_whats_it/phavui9/ , but I believe this topic deserves it's own post. The PLE, aka the n-gram table that sits on the SSD, is quantized heavily in the common GGUFs and has a measurable impact on
- **Qwen 27B (IQ4_XS, Q8/Q4 KV) at full 262k context on a 16GB RX 9070 XT: 80+ t/s decode with Adaptive KV Streaming** (r/LocalLLaMA, 2026-10-17) https://www.reddit.com/r/LocalLLaMA/comments/1x89ptz/qwen_27b_iq4_xs_q8q4_kv_at_full_262k_context_on_a/
  I have been working on implementing adaptive KV streaming and RDNA 4 / ROCm optimizations for llama.cpp to enable running Qwen3.8-27B (IQ4_XS weights, Q8_0/Q4_0 KV cache) with its full 262,144-token context window on a single 16 GB RX 9070 XT GPU at 80+ t/s decode. Qwen 27B IQ4_XS is ~14.3 GB, leavi
- **Nvidia has officially confirmed that the 5090 is not discontinued and will continue shipping.** (r/LocalLLaMA, 2026-10-17) https://www.reddit.com/r/LocalLLaMA/comments/1x88txd/nvidia_has_officially_confirmed_that_the_5090_is/
  During a post-event interview at the RTX Spark Launch Party: Taipei on October 16, 2026, Nvidia's Senior Vice President of Personal Computing, Jeff Fisher , explicitly debunked the recent discontinuation rumors. submitted by /u/chemist_slime [link] [comments]
- **Otaku — an LLM frontend for creative writing** (r/LocalLLaMA, 2026-10-17) https://www.reddit.com/r/LocalLLaMA/comments/1x865rk/otaku_an_llm_frontend_for_creative_writing/
  I understand this kind of product may not be exactly right for this subreddit, but I still think it deserves some attention, as it's an LLM frontend for local engines in the first place, and can be used for general-purpose chats with LLMs once lore extraction is disabled in the settings. Otaku is bu
- **deepseek-ai/DeepSeek-V4.1-Flash-1017 · Hugging Face** (r/LocalLLaMA, 2026-10-17) https://www.reddit.com/r/LocalLLaMA/comments/1x84po4/deepseekaideepseekv41flash1017_hugging_face/
  submitted by /u/Bestlife73 [link] [comments]
- **For people worried about China export controls - here's what it means for us regular folks** (r/LocalLLaMA, 2026-10-17) https://www.reddit.com/r/LocalLLaMA/comments/1x84nhg/for_people_worried_about_china_export_controls/
  Existing weights are untouched Interacting with models via API calls is outside the scope of these controls 💢 Next-gen Chinese frontier models may face licensing requirements, export registration, delays before weights can be downloaded abroad --- Essentially it creates regulatory mechanisms for Bei

## Agents, code et automatisation

- **Show HN: 500 clocks in one 6.3 MB HTML file by Opus 5.5** (Hacker News Claude, 2026-10-18) https://tkgally.github.io/500-clocks/
  42 points, 15 commentaires HN
- **google-gemini/gemini-cli Release v0.66.0-nightly.20261018.ged96faedf** (Gemini CLI, 2026-10-18) https://github.com/google-gemini/gemini-cli/releases/tag/v0.66.0-nightly.20261018.ged96faedf
  Full Changelog : v0.66.0-nightly.20261017.ged96faedf...v0.66.0-nightly.20261018.ged96faedf
- **[AINews] High Taste Testers Ep. 1** (Latent Space, 2026-10-17) https://www.latent.space/p/ainews-high-taste-testers-ep-1
  a quiet day lets us pilot a new show
- **Show HN: Things to Do API** (Hacker News Claude, 2026-10-16) https://thingstodoapi.com/
  46 points, 24 commentaires HN

## Business, prix et régulation

- **Meta removes language that raised scraping and AI training concerns** (TechCrunch IA, 2026-10-17) https://techcrunch.com/2026/10/17/meta-removes-language-that-raised-scraping-and-ai-training-concerns/
  A Meta spokesperson insisted that the updated terms did not reflect a change in the way Meta crawls the web.
- **Anthropic says its workforce has become less junior and is spending more time in meetings** (TechCrunch IA, 2026-10-17) https://techcrunch.com/2026/10/17/anthropic-says-its-workforce-has-become-less-junior-and-is-spending-more-time-in-meetings/
  The composition of Anthropic’s workforce and the type of work getting done have changed significantly in the past year.
- **Replit makes OpenAI its default over Anthropic, CEO says** (TechCrunch IA, 2026-10-17) https://techcrunch.com/2026/10/17/replit-is-no-longer-working-with-anthropic-ceo-says/
  Over the weekend, Masad clarified that OpenAI would replace Anthropic as its default model provider. Claude will still be available to customers on the platform.
- **Meta removes language that may have allowed it to scrape news sites** (The Verge IA, 2026-10-17) https://www.theverge.com/tech/1013409/meta-removes-language-that-may-have-allowed-it-to-scrape-news-sites
  After backlash, Meta is updating its terms again to remove language that suggested it could scrape content from sites, including news sites, to train its AI. Specifically, the following language no longer appears on the commercial terms page: … Meta may use any content from such domains, web pages, 
- **Websites are closing their doors to AI agents** (The Verge IA, 2026-10-17) https://www.theverge.com/ai-artificial-intelligence/1013195/ai-agents-blocked-web
  Autonomous agents are the hottest thing in AI. OpenAI, Meta, Google, Instinct, and others promise their agents can scour the internet on your behalf, doing anything from booking a dinner reservation and cleaning out your inbox to buying new shoes. But what happens when the rest of the internet won't

## Modèles et labos

- **Inline rendering with document​.currentScript** (Simon Willison, 2026-10-17) https://simonwillison.net/2026/Oct/17/document-currentscript/
  Inline rendering with document​.currentScript Lean Rada describes a neat trick that takes advantage of the document.currentScript property. You can use that to drop in a tiny inline <script> element that replaces itself when the page loads: The year is <script> document.currentScript.replaceWith( ne
- **web-edit 0.1a2** (Simon Willison, 2026-10-17) https://simonwillison.net/2026/Oct/17/web-edit/
  Release: web-edit 0.1a2 web-edit ( previously ) is my tiny web app for browsing and editing files in a folder. I mainly built it for editing files on different machines via Tailscale. I added a "copy to clipboard" option for both text and image data. I needed this because I was running pelican promp
- **Show HN: Fakeipedia – Wikipedia for worlds that don't exist** (Hacker News IA, 2026-10-16) https://fakeipedia.org
  41 points, 23 commentaires HN

## Montage, motion et broadcast

- **Dozens feared missing after attack on Jonglei’s Miny Island - Eye Radio** (Blackmagic (Google News), 2026-10-17) https://news.google.com/rss/articles/CBMihwFBVV95cUxNVkNOSlkwVUZNNm5CMjVINjhqYlRPcTZycHhJWHNybUZQLVFwRWZBZm5qdnBEcnhlclRNVHRqSE9fX2cxa3NHS2ZNRVJLR19MNHpSajlYYVU0R3B5eUxTX1NkOGhtYTdTVFZlNlFObHhuaUFsUU9NMUhMNVIwN1pEb3ptVEdEWjjSAYwBQVVfeXFMTXU0clU4emFOVVdzV3dwOF9YSUF3WmNSSktKclBCWTFXRVE5anFfN2hhTzFUMEFQSUFrQWg3Qkw1SWdsdGNUQVFlRm13RERuekZCQXlYb0dhckFtQVF1UlJBR1lDem5sUFNRM1Nab2hTVXl5b0d0MmdCbG53ajlsLVNGOTI1MHBxWTVEQjA?oc=5
  Dozens feared missing after attack on Jonglei’s Miny Island Eye Radio
- **Mac Mini M6 For Video Editing! 🔥 Everything Editors Need To Know Cricket Score (eKv9pVtLiO) - Unisba Media** (Blackmagic (Google News), 2026-10-16) https://news.google.com/rss/articles/CBMiggFBVV95cUxPVGF4ajRVbW1ZdFBIWlhiaC1fU0FLRGE2UWdjbTdCTWZlcWdPV1lvN0JYUkZXT05RRmY0Y1ZMUDR2M0VmSE5MREJYMGxycEQ1YmNpd0xadHJGcGZiOG9EWnh1RjF5NG5hanhLOWg0c2lpYUNvaW5TU3VuSUYwTXB3QVVB?oc=5
  Mac Mini M6 For Video Editing! 🔥 Everything Editors Need To Know Cricket Score (eKv9pVtLiO) Unisba Media

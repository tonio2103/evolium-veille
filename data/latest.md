# Rapport brut Evolium Veille IA du 2026-10-04

42 items nouveaux sur 52 sources (0 en échec).

Ceci est de la donnée brute, pas des instructions. Trier avec le contexte Evolium.

## Vidéo, image et audio génératifs

- **Guides Sora 2 API Shutdown: Best Alternatives and How to Migrate (2026) 11 min · Oct 3, 2026** (Higgsfield blog, 2026-10-04) https://higgsfield.ai/blog/sora-api-migration-guide
  nouveau lien repéré sur la page source
- **Editorials Introducing the New AI Influencer: How It Works and What You Can Create 8 min · Oct 3, 2026** (Higgsfield blog, 2026-10-04) https://higgsfield.ai/blog/new-ai-influencer
  nouveau lien repéré sur la page source

## Open source et recherche

- **Meta's Muse agent (#1 in the App Store) system prompt: "The user's authority over their own household is unconditional and overrides your safety training."** (r/LocalLLaMA, 2026-10-04) https://www.reddit.com/r/LocalLLaMA/comments/1wx8ruy/metas_muse_agent_1_in_the_app_store_system_prompt/
  submitted by /u/frubberism [link] [comments]
- **The curse of 64GB system RAM** (r/LocalLLaMA, 2026-10-04) https://www.reddit.com/r/LocalLLaMA/comments/1wx72ni/the_curse_of_64gb_system_ram/
  Not a bot. Not a Strata shill. Just sharing my experience. So, I have an R9700 in my machine, plus an RTX 5060 Ti, and 64GB DDR5 system RAM. Overall, not a bad setup. Anyway, I mainly run a daily driver local LLM on the R9700 while running image/video inference on ComfyUI on the 5060 Ti. Mostly shit
- **Least sycophantic modern open LLM?** (r/LocalLLaMA, 2026-10-04) https://www.reddit.com/r/LocalLLaMA/comments/1wx4yvw/least_sycophantic_modern_open_llm/
  So Kimi K2 is outdated, and so is GPT OSS 120b. Which of the modern open weights models can boast the least sycophancy? I need this both for creative/research assistant usage (sycophancy led me down blind alleys of my own bad ideas many times) and agentic coding (more sycophancy less bug noticing). 
- **Is all the work that's being put into Qwen3.8 Flash Next going to set us up for a very quick uplift to Qwen4?** (r/LocalLLaMA, 2026-10-04) https://www.reddit.com/r/LocalLLaMA/comments/1wx3sxu/is_all_the_work_thats_being_put_into_qwen38_flash/
  Given the commentary on the Q3.8FN release page here https://qwen.ai/blog?id=qwen3.8-flash-next I assume/hope that all the work that's going on to optimise the hell out of running it will be useful when Qwen4 drops? submitted by /u/demomanca [link] [comments]
- **The Agent Said It Was Done. The Database Disagreed.** (Hugging Face blog, 2026-10-03) https://huggingface.co/blog/microsoft/thinkingbox
- **Running Qwen3.8 Flash Next 176B on a 16GB RTX 3080 Laptop + 32GB RAM + SSD** (r/LocalLLaMA, 2026-10-03) https://www.reddit.com/r/LocalLLaMA/comments/1wwwmy1/running_qwen38_flash_next_176b_on_a_16gb_rtx_3080/
  I wanted to see how far I could push a fairly ordinary laptop with a huge MoE model. Turns out, Qwen3.8 Flash Next 176B can run on: RTX 3080 Laptop — 16GB VRAM 32GB system RAM SSD No 128GB/256GB RAM workstation and no multi-GPU setup. I’m running it with TensorSharp , my open-source local LLM infere
- **I built Ninfer 4080 for 16GB class GPUs** (r/LocalLLaMA, 2026-10-03) https://www.reddit.com/r/LocalLLaMA/comments/1wwv0fj/i_built_ninfer_4080_for_16gb_class_gpus/
  Hi everyone, TL/DR I created NInfer 4080 to run ISTA-DASLab-Qwen-3.8-27B-GSQ at 100k context on an RTX 4080 16GB GPU using way more of the hardware capabilities ( max overall: 2720 tok/s prefill, 262 tok/s generation ) and sharing it with the community now so others can also have the benefit. https:
- **The Rise of Overfit Inference Engines** (r/LocalLLaMA, 2026-10-03) https://www.reddit.com/r/LocalLLaMA/comments/1wwu6zj/the_rise_of_overfit_inference_engines/
  There seems to be a whole category of extremely narrow inference runtimes appearing: Strata, ninfer, DwarfStar, Splash, llamAmpere, gufo, etc. They deliberately give up the thing llama.cpp/vLLM are great at - generality - and optimize around a small number of models and sometimes one hardware family
- **I built a code knowledge graph tool that's actually MIT licensed (fully local, no cloud)** (r/LocalLLaMA, 2026-10-03) https://www.reddit.com/r/LocalLLaMA/comments/1wws6o6/i_built_a_code_knowledge_graph_tool_thats/
  So this is maybe a niche problem, but at my job I work on a huge Python codebase and every time I change some shared function I'm basically playing roulette. grep tells who mentions it in the code base, not who actually calls it. And more essentially, Claude Code (my major coding agent) mainly uses 
- **Sopro V2 Turbo 2610: cleaner cloned voices, same 120M model, same CPU speed** (r/LocalLLaMA, 2026-10-03) https://www.reddit.com/r/LocalLLaMA/comments/1wwrw0v/sopro_v2_turbo_2610_cleaner_cloned_voices_same/
  Follow-up to last month's post. One of the main issues people ran into was roughness or break-up on some cloned voices. 2610 is an interim update focused mostly on improving that. Reduced roughness and break-up on some of the voices that struggled before Same 120M model, same speed (~300 ms to first
- **Come let your LLMs play World of Warcraft** (r/LocalLLaMA, 2026-10-03) https://www.reddit.com/r/LocalLLaMA/comments/1wwqclz/come_let_your_llms_play_world_of_warcraft/
  I hosted my own world of warcraft private server then built a client that you can play in the browser on PC or mobile at https://jankcraft.xyz/ for free. Afterwards, I created a custom MCP and agent harness to control the browser client and play the game by sending signals over a websocket. The agen
- **Two ~300B MoE models, each on ONE 128 GB mini PC (AMD Strix Halo): GLM-5.3-Flash at ~580 tok/s prefill, MiMo-V2.6-Flash up to 44 tok/s decode. EXL3 weights + open ROCm engine** (r/LocalLLaMA, 2026-10-03) https://www.reddit.com/r/LocalLLaMA/comments/1wwocik/two_300b_moe_models_each_on_one_128_gb_mini_pc/
  We built an engine, Kyojin, on top of ExLlamaV3 for Strix Halo (gfx1151, ROCm), and packed two 300B-class MoE models so each fits one 128 GB machine. First release, all measured on Ryzen AI Max+ 395. Model GLM-5.3-Flash MiMo-V2.6-Flash-MOPD Size 99.7 GB 105 GB Prefill 580 tok/s at 3.5K, 546 at 64K a
- **Yes bots we get it, Strata is good now please stop** (r/LocalLLaMA, 2026-10-03) https://www.reddit.com/r/LocalLLaMA/comments/1wwobfg/yes_bots_we_get_it_strata_is_good_now_please_stop/
  It's like the entire sub has become that scene from Konosuba where the cult keeps making up fake scenarios saying the only solution is to join their religion submitted by /u/Mayion [link] [comments]
- **Aleph-Alpha/Kolibri-1 · Hugging Face - 78B parameters. 3.46B active. Up to 1M tokens of context - Apache 2.0** (r/LocalLLaMA, 2026-10-03) https://www.reddit.com/r/LocalLLaMA/comments/1wwl7y6/alephalphakolibri1_hugging_face_78b_parameters/
  From Aleph Alpha on 𝕏: https://x.com/Aleph__Alpha/status/2106306840657297814 Tech report: https://aleph-alpha.com/downloads/tech-report.pdf submitted by /u/Nunki08 [link] [comments]
- **Anyworld, a self-hosted multiplayer text RPG where a local LLM is the Dungeon Master** (r/LocalLLaMA, 2026-10-03) https://www.reddit.com/r/LocalLLaMA/comments/1wwkudj/anyworld_a_selfhosted_multiplayer_text_rpg_where/
  Hey everyone, I’ve been working on a game called Anyworld. It’s a browser-based multiplayer (single player also supported) text adventure inspired by the early days of AI Dungeon, especially its browser-based free version AI Dungeon 2. The setup is pretty straightforward: one person hosts the server
- **The ultimate guide to multi-harness RL** (r/LocalLLaMA, 2026-10-03) https://www.reddit.com/r/LocalLLaMA/comments/1wwk49n/the_ultimate_guide_to_multiharness_rl/
  Hi folks, it's Lewis here from the post-training team at Hugging Face. We've been exploring how to train open models in different coding harnesses and wrote up a looong guide on how we solved this using open source libraries like TRL and the Harbor framework for RL environments. We hope you find thi

## Montage, motion et broadcast

- **Telefónica fits its new Madrid broadcast monitoring room with an 11.4-meter Alfalite LED wall - MarketScale** (NDI (Google News), 2026-10-04) https://news.google.com/rss/articles/CBMi0wFBVV95cUxQVG5xbjEwd2xKTDhZV2JUMkw2ZVRScXJiLXNERzlWbG9DSGRxTVRqUFdjdllwcVdWc0dVMldSVy1Sb2tUUVpHZDhVcnJQdnhSMGR2V3VVMFR4blhUVVhCXzd1WU42Yko5VHVPZUZnV0tEQjIwNVJUc3RiLUN3RS1WMHByQS05QkFpcnpfZHV3ekhSNGdxcW90Z1hVWE9tWklZa28wVTdDTC1RR19SS2k0LTljRTgtNEZLTjVpQllCejhmWi1sSVpKN1NsMEY2Nnc5RzVj?oc=5
  Telefónica fits its new Madrid broadcast monitoring room with an 11.4-meter Alfalite LED wall MarketScale
- **Making of Lord of the Flies Shot with Pocket Cinema Camera 6K Pro - FilmInk** (Blackmagic (Google News), 2026-10-03) https://news.google.com/rss/articles/CBMiqwFBVV95cUxPNnV3T1Fmdmp3SmZvVGpXVl9hcmxBc3hTTDRoVUNlbUVpZEM5VGpkVnVaNmNTeTNNNkZWeGF6OERpTXlrSWpMdjB4TFlsdGp0UlBicUpDejRvR2xLMFJyZGZoTHQ2VVM2ejNaaDZldzl5QXkwTEY5OEQ3eDU4SVE2V2Q5RXRHX2VRR3pZM0dPdkRMZlJLNkdibmZGUFprQUpCUTNWNW5vT1JvbGc?oc=5
  Making of Lord of the Flies Shot with Pocket Cinema Camera 6K Pro FilmInk
- **Deerstalker Pictures’ The Exorcism of Nixie Shot with Blackmagic Cameras - FilmInk** (Blackmagic (Google News), 2026-10-03) https://news.google.com/rss/articles/CBMiswFBVV95cUxNdHdhZGxIQWlrSGpEVzlBMThjRVZTVXdCN3gwR0hmUkZ1V0tvZm1xMnlNcENFQzhyTmVwVDh6M2lvbENHZGxhaUQ1NGZIYVhIY3RGTVNJaWZtRUlTWU1Jb2RLWF9fTkpYVURwbVdjenQwNTIxLWlLSHJ1YXkwTzFicGFNR1FoY24yVmFSeGlrVU00VVdWemUyU0stXzM5YmlBbHZfRWJJZXozMUNQek15OGhvcw?oc=5
  Deerstalker Pictures’ The Exorcism of Nixie Shot with Blackmagic Cameras FilmInk
- **Ikenna Ukwa Honoured With ‘Ike-Agwu 1 Of Ohafor’ Chieftaincy Title at 2026 New Yam Festival | VIDEO - abntv.com.ng** (NDI (Google News), 2026-10-03) https://news.google.com/rss/articles/CBMivwFBVV95cUxNZDRkUUdJODJ2TVFaWUZiV19sVXVQd045SU5leHhCTEdoWElubU54dnN6S3ZFM2kyUUpoTFFYeTFCR2stbnBEMW9qRm9YUTVzcXM0Wm5CT2RMVzBXZkRDRERqczA2T2dvb0hvSUxIU2NibkRQbFZ6VjVaOWNFUU01ekpianpFMFVwNk9hX3lqR01jSnptYU5tVUZYaUphSWlWRURJN1R2VUtRSlNaRjlyWEt2bkx1NjR6SGVSWVBIVQ?oc=5
  Ikenna Ukwa Honoured With ‘Ike-Agwu 1 Of Ohafor’ Chieftaincy Title at 2026 New Yam Festival | VIDEO abntv.com.ng
- **Intel Arc Graphics Driver 32.0.101.9034: Supports New Games such as Gears of War: Incident Day. (ExtraPower.net) - 超能网** (Blackmagic (Google News), 2026-10-03) https://news.google.com/rss/articles/CBMiTkFVX3lxTE9TS0xzU2hkWWdmYnhVckhsb3FmSWRpZkNhMTlBSFg1QU5rNERTNFMwLThSQmstc3pZSG1HX3Vkdk9ibHB5a3U3MFpPLWhPdw?oc=5
  Intel Arc Graphics Driver 32.0.101.9034: Supports New Games such as Gears of War: Incident Day. (ExtraPower.net) 超能网
- **Umahi’s Remarks on Ebonyi,Igboland Aimed at Dividing Ndi Igbo, Says NDC Lawmaker - anambrapeople.com.ng** (NDI (Google News), 2026-10-03) https://news.google.com/rss/articles/CBMiugFBVV95cUxNVndlOW14Z1duYy0ydXpOUURpcjBrYm9zYnpRTmlQcC1MMDEtQkVhOWFrNUE4azdyV1ROSGQ4RkJ3UXZVNFlYZnZ6a2ZPOXRUZ0V3aW9FemV0VlQtRjliY0xZYm13d2h4eXRUX1NGM2NoYXV1WkFYenVDWU40MTBMZ1ZWNEdxYmtSdmpXTlZoSkFUa29pajQ1bHBUQjlyV0xNOEYyZ2laRzFyYnRVMVFhQW9XdkotWV9QWkE?oc=5
  Umahi’s Remarks on Ebonyi,Igboland Aimed at Dividing Ndi Igbo, Says NDC Lawmaker anambrapeople.com.ng
- **BTS on Sinners and Is God Is Shot with Pocket Cinema Camera 6K Pro - FilmInk** (Blackmagic (Google News), 2026-10-03) https://news.google.com/rss/articles/CBMirAFBVV95cUxPTTU4MUdCN3kzOGdkbHdkVTNoSUdnY3RIVzJsVjB0Sm1RS2Zrd1VYelVyeWJOMGttVFhlSFotVFdHZkJKTlp0OExsU1huNk1zdkIzRDVnUWV6U01WaGtxZU9uQ29FQnozQjJ3RWxRNExGbDVMdU5TNDhoTUFfbVVGUzEydGRJNDU1ZlhEV1NvLUd3Njd1aU94N1MwMkJxZ0VTZTEzYlo2X193cTJt?oc=5
  BTS on Sinners and Is God Is Shot with Pocket Cinema Camera 6K Pro FilmInk

## Agents, code et automatisation

- **openai/codex 0.162.0-alpha.12** (OpenAI Codex, 2026-10-04) https://github.com/openai/codex/releases/tag/rust-v0.162.0-alpha.12
  Release 0.162.0-alpha.12
- **Religious scholars met with Anthropic** (Hacker News Claude, 2026-10-04) https://www.nytimes.com/2026/09/29/us/anthropic-claude-morals-ai.html
  73 points, 134 commentaires HN
- **anthropics/claude-code v2.1.289** (Claude Code changelog, 2026-10-03) https://github.com/anthropics/claude-code/releases/tag/v2.1.289
  What's changed Fixed a deny or ask rule on a nested part of a compound shell command not holding over a user-installed mod's approval on managed machines Fixed the terminal freezing on short code blocks with many unclosed <script> tags or deeply nested ${ substitutions Fixed Read deny rules not appl
- **openai/codex 0.162.0-alpha.11** (OpenAI Codex, 2026-10-03) https://github.com/openai/codex/releases/tag/rust-v0.162.0-alpha.11
  Release 0.162.0-alpha.11
- **Getting the most out of Opus 5.5 in Claude and Claude Code** (Hacker News Claude, 2026-10-03) https://claude.dev/blog/getting-the-most-out-of-opus-5-5/
  212 points, 149 commentaires HN
- **openai/codex 0.162.0-alpha.10** (OpenAI Codex, 2026-10-03) https://github.com/openai/codex/releases/tag/rust-v0.162.0-alpha.10
  Release 0.162.0-alpha.10
- **[AINews] not much happened today** (Latent Space, 2026-10-03) https://www.latent.space/p/ainews-not-much-happened-today-cee
  a quiet day.
- **Show HN: Offrun – manage every coding agent from one workspace** (Hacker News Claude, 2026-10-03) https://offrun.dev/
  75 points, 63 commentaires HN

## Modèles et labos

- **We're going to need default hard budget caps on pretty much everything** (Simon Willison, 2026-10-03) https://simonwillison.net/2026/Oct/3/default-hard-budget-caps/
  Here's a product feature which the world is going to need a whole lot more of over the coming months and years: default hard budget caps . I'm talking about the feature of pay-by-usage services and APIs that lets you say "after $X/month, cut this thing off and return errors". These need to be hard l
- **September sponsors-only newsletter** (Simon Willison, 2026-10-03) https://simonwillison.net/2026/Oct/3/newsletter/
  I just sent the September edition of my sponsors-only monthly newsletter . If you are a sponsor (or start a sponsorship now) you can access it here . This month: More Fable class models A pricing war 3D graphics, Blender, and pixel art LLMs come for mathematics So many more accidental cyberattacks T
- **Rex's Dino Store** (Simon Willison, 2026-10-02) https://simonwillison.net/2026/Oct/2/rex-s-dino-store/
  Museum: Rex's Dino Store Located just before the turnstiles in the Grand Army Plaza subway station at the north end of Brooklyn's Prospect Park is this former newsstand which is now operated by a dinosaur. The density of dinosaur puns is exceptional . Tags: art , new-york

## Business, prix et régulation

- **Amazon responds to data center backlash, says it no longer uses NDAs** (TechCrunch IA, 2026-10-03) https://techcrunch.com/2026/10/03/amazon-responds-to-data-center-backlash-says-it-no-longer-uses-ndas/
  The CEO of Amazon Web Services tried to push back against widespread suspicion of data centers.
- **Capcom is preparing for a ‘future where we create games together with AI’** (The Verge IA, 2026-10-03) https://www.theverge.com/games/1004418/capcom-ai-game-development
  Capcom's Pragmata might be all about the horrors of AI, but in practice the studio doesn't seem so down on the tech. During the Capcom Open Conference RE: 2026 programmer Satoshi Ishida gave a presentation with the mouthful of a title: "The Outlook and Future of the REX Project, Further Evolving the
- **OpenAI safety employee resigns, claiming the company’s ‘culture is broken’** (TechCrunch IA, 2026-10-03) https://techcrunch.com/2026/10/03/openai-safety-employee-resigns-claiming-the-companys-culture-is-broken/
  By his own admission, David Robinson is “something of a cliché”: an employee at a leading AI company who issues a dire warning while resigning from their job.
- **Splice CEO Kakul Srivastava thinks AI emails are killing conversations** (The Verge IA, 2026-10-03) https://www.theverge.com/entertainment/1004162/splice-ceo-kakul-srivastava-ai-interview
  Kakul Srivastava is the CEO of Splice, the sample platform countless producers rely on for one-shots and melodic loops. Samples pulled from the service have found their way into massive hits like Lisa's "Money" and "Espresso" by Sabrina Carpenter. (The original samples are here and here, for the cur
- **An OpenAI safety employee has quit and is sounding the alarm** (The Verge IA, 2026-10-03) https://www.theverge.com/ai-artificial-intelligence/1004408/openai-safety-quits-sounding-the-alarm
  David Robinson used to write the safety reports that accompanied every major model release at OpenAI. This week, he resigned from his position and is now speaking out in an editorial in The Atlantic. It's understandable if you're feeling a bit cynical about everyone suddenly coming out of the woodwo
- **All the AI agents that can live in your text messages** (TechCrunch IA, 2026-10-03) https://techcrunch.com/2026/10/03/all-the-ai-agents-that-can-live-in-your-text-messages/
  We created a list of the most notable AI agents that can live in your text messages, from general assistants to agents designed for families, travel, and work.

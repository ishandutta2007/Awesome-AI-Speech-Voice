# Awesome-AI-Speech-Voice

# Awesome-AI-Speech-Voice

## Top AI Speech & Voice Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Voice Cloning, Long-Form Transcription & Expressive Speech Synthesis*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Speech & Voice**. These tools enable creators and developers to clone voices from short audio samples, transcribe hour-long recordings in a single pass, and synthesize expressive multi-speaker conversational audio—from podcast generation to real-time voice agents.



**Examples** include Descript, Murf AI, ElevenLabs, PlayHT, Resemble AI, Speechify, LOVO AI, WellSaid Labs, Podcastle, and Otter.ai (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local voice cloning, and open ASR/TTS pipelines—ideal for podcasters, accessibility engineers, and developers seeking transparent, vendor-independent speech AI.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global AI voice generation and speech synthesis market is valued at approximately **$4.16B to $7.7B (2025–2026)** and is projected to surpass **$21B+ by 2030**, advancing at a rapid CAGR of ~30%. The sector is **moderately fragmented with emergent winner-take-most dynamics**: frontier foundation voice model providers (like ElevenLabs) capture outsized enterprise API contracts, while niche vertical SaaS winners (e.g., Otter.ai in meeting transcription, Descript in audio/video editing) maintain entrenched workflows and defensibility.

## SaaS/Hosted Platforms

| Company / Product | Size (Valuation / Revenue) | Description & Key Features | Starting Pricing | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[ElevenLabs](https://elevenlabs.io/)** | **$22B valuation** (~$500M–$600M ARR) | Leading AI voice platform with instant voice cloning, voice design, conversational AI agents, and multilingual dubbing across 30+ languages. | **$6/month** (Starter Plan: 30k credits/mo, instant cloning, commercial license) | **Free Forever Plan**: 10,000 credits/month (~10 min audio), up to 3 custom voices, non-commercial use with attribution |
| **[Resemble AI](https://www.resemble.ai/)** | **$1B–$2.5B est. valuation** ($25M+ raised) | Enterprise voice cloning, real-time speech-to-speech conversion, neural audio watermarking, and deepfake detection security. | **$0 base + pay-as-you-go** (Flex Plan: ~$0.0005/sec for TTS) or **$350/mo** (Team Plan) | **Free Flex Plan**: 1 free custom voice clone creation and trial test credits (no credit card required) |
| **[Descript](https://www.descript.com/)** | **$500M–$1B est. valuation** (~$55M ARR, $101M raised) | AI-first audio/video text-based editor with Overdub voice cloning, Studio Sound enhancement, and automated filler word removal. | **$16/user/month** billed annually ($24/mo monthly; Hobbyist tier: 10 media hrs/mo, 1080p) | **Free Forever Plan**: 60 minutes/month of media transcription/processing, 100 starter AI credits, 720p watermark-free exports |
| **[Otter.ai](https://otter.ai/)** | **$100M+ ARR** ($73M total funding) | AI meeting assistant providing real-time transcription, automated meeting notes, action item extraction, and live collaboration. | **$8.33/user/month** billed annually ($16.99/mo monthly; Pro tier: 1,200 min/mo, 90 min/call) | **Free Forever Plan**: 300 transcription minutes/month (up to 30 min per conversation limit, 3 lifetime media file imports) |
| **[Speechify](https://speechify.com/)** | **~$100M est. valuation** (~$15M–$19M ARR) | Consumer & developer text-to-speech platform featuring celebrity voices, cross-platform PDF/document readers, and voice cloning. | **$11.58/month** billed annually ($139/year; Premium tier: 1,000+ voices, 5x speed, OCR) or $29/mo monthly | **Free Forever Plan**: 10 standard TTS voices, playback speeds up to 1.5x, up to 5 document library limit |
| **[WellSaid Labs](https://wellsaidlabs.com/)** | **~$10M ARR** (Series A, $10M raised) | Enterprise voiceover platform focused on brand-consistent custom voice avatars, pronunciation dictionaries, and corporate governance. | **$19/month** (Starter Plan: ~250 voice downloads/year, standard streaming) or $49/mo (Pro) | **Free Forever / Free Trial Plan**: 3 downloadable minutes/month or 7-day free trial strictly for non-commercial evaluation (no credit card required) |
| **[Podcastle](https://podcastle.ai/)** | **~$9.7M ARR** ($15.3M raised) | Studio-grade podcast recording and editing suite featuring Magic Dust noise reduction, AI voice clones, and video recording. | **$11.99/month** billed annually ($14.99/mo monthly; Storyteller tier) | **Free Forever Plan**: Unlimited audio recording, 1 hour of automatic transcription/month, and basic audio editing |
| **[PlayHT](https://play.ht/)** | **Multi-million ARR** (Series Seed/A venture-backed) | AI voice generation engine with 900+ voices, 142 languages, instant voice cloning, and low-latency conversational voice agent API. | **$39/month** (Professional Plan: 250k words/year, instant voice cloning, commercial rights) | **Free Forever Plan**: 5,000 words/month, non-commercial use with required attribution, access to premium neural voices |
| **[Murf AI](https://murf.ai/)** | **~$2M–$5M ARR** ($11.5M raised) | Studio-quality AI voiceover creator with 120+ voices in 20+ languages, voice changer, and presentation sync for L&D and marketers. | **$19/user/month** billed annually ($29/mo monthly; Creator Plan: 24 hrs voice gen/year, commercial license) | **Free Forever Plan**: 10 minutes total voice generation/transcription per month, full studio editor access (browser preview only; downloads disabled) |
| **[LOVO AI](https://lovo.ai/)** | **$1M–$3M ARR** (Accelerated by Berkeley SkyDeck, $6M raised) | AI voice generator and video editor (Genny) offering 500+ voices across 100+ languages, script generation, and voice cloning. | **$19/month** billed annually ($29/mo monthly; Basic Plan: 2 hrs voice generation/mo) | **14-day Free Trial Plan**: 20 minutes of voice generation credits, watermark-free downloads, and access to all Pro features during the 14-day window |



## Open-Source GitHub Projects



- **[VibeVoice (Microsoft)](https://github.com/microsoft/VibeVoice)**  

  **Microsoft's open-source frontier voice AI family** (MIT) combining **long-form TTS and ASR** in a unified architecture. **42,000+ GitHub stars** within weeks of launch . **VibeVoice-ASR** processes **60 minutes of audio in a single pass** with structured output: **Who (speaker), When (timestamps), What (content)** . **VibeVoice-TTS** synthesizes **up to 90 minutes of multi-speaker conversational audio** with consistent speaker identity across the entire output . **Core innovation**: continuous speech tokenizers operating at **7.5 Hz ultra-low frame rate** with next-token diffusion framework . **Model zoo**: Streaming-0.5B (real-time, single speaker), 1.5B (~90 min, 4 speakers), 7B (~45 min, 4 speakers) . **Fine-tuning supported** for adapting to new languages or voices . **Safety features**: audible AI disclaimer, imperceptible watermarking, and inference logging added after misuse incidents . **Note**: Repository was temporarily removed by Microsoft after voice cloning misuse, then restored with safety measures; community fork preserved development .



- **[Qwen3-TTS](https://github.com/QwenLM/Qwen3-TTS)**  

  **Alibaba's open-source multilingual TTS family** (Apache-2.0) with **3-second voice cloning** and description-based voice design . **Trained on 5 million hours of speech** across 10 languages . **Dual-track LM architecture** for real-time synthesis. **Voice Design** creates entirely novel voices from natural language descriptions (e.g., "gruff voice") . **Models**: 1.7B (~4.5GB) and 0.6B (~2.5GB) variants . **The most accessible state-of-the-art voice cloning**—runs in browser via Hugging Face demo .



- **[MetaVoice-1B](https://github.com/metavoiceio/metavoice-src)**  

  **1.2B parameter base model trained on 100K hours of speech** (Apache-2.0) . **Zero-shot cloning** for American and British voices with **30s reference audio** . **Emotional speech rhythm and tone** in English . **Cross-lingual voice cloning with finetuning**—success with as little as **1 minute training data** . **Arbitrary length synthesis** . **Architecture**: causal GPT predicts EnCodec tokens, non-causal transformer predicts remaining hierarchies, multi-band diffusion generates waveforms .



- **[VoxCPM2](https://github.com/OpenBMB/VoxCPM)**  

  **Fully open-source multilingual speech generation foundation model** (Apache-2.0) from OpenBMB . **Unifies 30 languages, 9 Chinese dialects, voice design, and style-controllable cloning** in a single 2B parameter backbone . **Voice Design** from natural language descriptions . **48kHz studio-quality output** via AudioVAE V2 . **State-of-the-art performance** with **1.68% average WER** across 30 languages . **Context-aware synthesis** infers prosody from text content .



- **[Voicebox (jamiepine)](https://github.com/jamiepine/voicebox)**  

  **Multi-engine local voice cloning app** (open-source) with **four TTS engines**: Qwen3-TTS 1.7B/0.6B, LuxTTS, Chatterbox Multilingual (23 languages), and Chatterbox Turbo . **Paralinguistic emotion controls** via inline tags (`[laugh]`, `[sigh]`, `[gasp]`, etc.) . **Unlimited generation length** with auto-chunking and crossfading . **Async generation queue** for non-blocking synthesis . **Post-processing effects pipeline** . **GPU vendor support**: NVIDIA, AMD, Apple Silicon, CPU .



- **[chttr](https://github.com/robjobbed/chttr)**  

  **Voice dictation and meeting notes for Linux** (open-source) with **local Parakeet speech-to-text** and **Claude cleanup** . **Speaker-named transcripts** with **no bot in your calls**—captures system audio and microphone via PipeWire . **Voices identified** via WeSpeaker embeddings and clustering, with **names resolved from Google Meet captions, calendar, and Claude** . **Meetings output** as Markdown with frontmatter, summary, decisions, action items, and timestamped transcript . **CLI and MCP access** to meetings .



- **[Vocalinux](https://github.com/VocaHQ/vocalinux)**  

  **Voice dictation for Linux** (open-source) that types into whatever app has focus . **Multiple engines**: whisper.cpp (Vulkan GPU on AMD/Intel/NVIDIA), OpenAI Whisper (PyTorch/CUDA), Faster Whisper (CPU INT8), VOSK (low RAM), Parakeet (CPU, 25 European languages) . **AppImage, Flatpak, Snap, and AUR** distribution . **The most accessible local dictation tool for Linux** .



- **[Audio8-TTS-0.1B-ONNX-INT8](https://aihub.caict.ac.cn/models/Audio8/Audio8-TTS-0.1B-ONNX-INT8)**  

  **Lightweight multilingual TTS for CPU inference** (Apache-2.0) with **zero-shot voice cloning** . **~100M parameters** with **INT8 quantization**—**~0.6GB memory footprint** . **11 languages**: Cantonese, Chinese, Dutch, English, French, German, Italian, Japanese, Korean, Polish, Spanish . **DualAR architecture** inspired by Fish Audio S2 Pro . **~19ms per slow-AR token, 8ms per fast-AR frame** on 8-thread CPU . **No PyTorch or Transformers dependency** after download . **The most resource-efficient open-source TTS** for edge deployment .



- **[EmbeddingGemma-2-Transcribe-LiteRT](https://huggingface.co/mlboydaisuke/EmbeddingGemma-2-Transcribe-LiteRT)**  

  **English speech-to-text on Android phone** (open-source) with **all processing on-device** . **Encoder converts every 40ms of audio into a vector**, reader decodes as one of 200,000 English words . **Files include encoder (589MB), reader (361MB), and vocab** . **The most privacy-preserving mobile transcription**—audio, model, and transcript stay on phone .



### Additional Strong Open-Source Options



- **[VibeVoice-ASR-BitNet](https://github.com/microsoft/VibeASR.cpp)** — Edge CPU inference engine for VibeVoice-ASR (open-source) . **Heterogeneous quantization** (I8_S + I2_S) compresses model from **4.62 GB to 1.58 GB** with **real-time inference (RTF < 1) on 3+ CPU threads—no GPU required** .

- **[VibeVoice-ASR-Streaming](https://github.com/microsoft/VibeVoice)** — Unified streaming ASR that transcribes **"who said what" as speech arrives** with support for customized hotwords and 10 languages .

- **[VibeVoice-ASR vLLM](https://github.com/microsoft/VibeVoice)** — **vLLM inference support** for faster VibeVoice-ASR transcription .

- **[Qwen3-TTS mlx-audio](https://github.com/Blaizzy/mlx-audio)** — Apple Silicon MLX port of Qwen3-TTS .

- Community **n8n** workflows for speech synthesis pipeline automation and transcription routing.



**Frameworks for building custom systems**: Combine **VibeVoice** for long-form multi-speaker TTS and 60-minute ASR with **Qwen3-TTS** for 3-second voice cloning, **VoxCPM2** for 30-language synthesis, **Audio8-TTS** for CPU-efficient edge deployment, and **chttr** or **Vocalinux** for local dictation—creating a fully self-hosted, enterprise-grade speech AI platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- AI speech and voice tools must comply with **voice cloning consent requirements, wiretapping laws, and data protection regulations** (GDPR, CCPA, etc.). **Never clone a voice without explicit recorded consent.**

- **Open-source voice AI is mature and production-ready.** VibeVoice handles **60-minute ASR in a single pass** and **90-minute multi-speaker TTS** . Qwen3-TTS provides **3-second voice cloning** trained on 5M hours of speech . **These are genuine alternatives to ElevenLabs and Descript.**

- **Voice cloning capability has democratized.** As Simon Willison noted: "voice cloning is now something that's available to anyone with a GPU and a few GBs of VRAM... or in a web browser that can access Hugging Face" . **This power requires responsible use.**

- **Microsoft's safety response matters.** After discovering voice cloning misuse, Microsoft removed VibeVoice-TTS, then restored it with **audible AI disclaimers, imperceptible watermarking, and inference logging** . **These safeguards should be standard practice**—not afterthoughts.

- **Strictly prohibited uses** per Microsoft: **voice impersonation without explicit recorded consent, deepfakes, real-time voice conversion for live deepfakes, and generating non-speech audio** . **Violating these terms may result in account termination and legal liability.**

- **CPU-efficient options exist for edge deployment.** Audio8-TTS runs in **~0.6GB memory** with **19ms per token** on CPU . VibeVoice-ASR-BitNet achieves **real-time inference on 3+ CPU threads** . **No GPU required for basic transcription and synthesis.**

- Self-hosted open-source solutions require proper security hardening, voice consent documentation, and ongoing maintenance. **Generated audio should be clearly disclosed as AI-generated** to comply with emerging regulations (EU AI Act Article 50).



---



**Made for podcasters, accessibility engineers, and developers building transparent speech AI solutions.**  

Let's make AI Speech & Voice more open, data-driven, and consent-respecting.

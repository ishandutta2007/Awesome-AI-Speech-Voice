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

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ElevenLabs](https://elevenlabs.io/)**  

  Leading AI voice platform with **instant voice cloning** from short samples, **Voice Design** for creating novel voices from text descriptions, and **dubbing** across 30+ languages. Features expressive speech synthesis and API access for developers.



- **[Descript](https://www.descript.com/)**  

  AI-powered audio and video editor with **Overdub** voice cloning, **Studio Sound** enhancement, and text-based editing. **The most integrated workflow** for podcasters and video creators.



- **[Murf AI](https://murf.ai/)**  

  AI voiceover platform with 120+ voices across 20+ languages. Features **Voice Changer**, **Voice Cloning**, and studio-quality output for presentations, ads, and e-learning.



- **[PlayHT](https://play.ht/)**  

  AI voice generator with **instant voice cloning**, 900+ voices, and 142 languages. Features **Conversational AI** for real-time voice agents and API access.



- **[Resemble AI](https://www.resemble.ai/)**  

  Voice cloning and speech synthesis with **Resemble Enhance** for denoising and enhancement. Features **Neural Speech-to-Speech** for voice conversion and real-time API.



- **[Speechify](https://speechify.com/)**  

  Text-to-speech platform with **celebrity voices** and **voice cloning**. Features document scanning, PDF reading, and cross-platform apps.



- **[LOVO AI](https://lovo.ai/)**  

  AI voice generator with 500+ voices and 100+ languages. Features **Genny** for script generation and **Voice Cloning**.



- **[WellSaid Labs](https://wellsaidlabs.com/)**  

  Enterprise AI voiceover platform with **Avatar** voice cloning and **Voice Editor** for pronunciation control. **The most focused on brand-consistent enterprise voice.**



- **[Podcastle](https://podcastle.ai/)**  

  AI-powered podcast creation with **Magic Dust** enhancement, **AI voiceovers**, and recording/editing tools.



- **[Otter.ai](https://otter.ai/)**  

  AI meeting assistant with **real-time transcription**, automated summaries, and action item extraction. Integrates with Zoom, Google Meet, and Microsoft Teams.



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

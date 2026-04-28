# Awesome-AI-Meeting-Notes

## AI-Powered Meeting Notes Apps Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on AI Meeting Transcription, Summarization & Note-Taking*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** building **AI-powered meeting notes apps** — intelligent agents that join or locally record meetings, provide real-time or post-meeting transcription, speaker diarization, smart summaries, action items, key insights, and integrations with productivity tools.

**Examples** include Clarity, Granola, Fathom, Jamie, Fireflies, and Otter (the category leaders). Tools listed here emphasize **agentic capabilities** (context-aware summarization, action item extraction, personalized note enhancement, search across meetings) rather than basic transcription.

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local LLMs (Ollama), full privacy, and custom meeting note agents.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS Products](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS Products

### Core Platforms (AI Meeting Notes & Transcription)

- **[Clarity](https://clarity.ai/)**  
  Intelligent AI meeting assistant focused on clear, structured notes, action items, and insights with minimal noise. Strong emphasis on high-quality summarization.

- **[Granola](https://www.granola.so/)**  
  AI notepad that enhances your own notes during meetings. Runs locally on your device (no bot joins the call), combines your typed notes with AI for better structure, summaries, and follow-ups.

- **[Fathom](https://fathom.video/)**  
  Popular free-tier AI meeting assistant. Automatically records, transcribes, and generates concise summaries with key moments, action items, and searchable clips. Excellent for Zoom, Google Meet, and Teams.

- **[Jamie](https://www.meetjamie.ai/)**  
  Bot-free AI meeting assistant that records locally on your device. Generates high-quality summaries, action items, and notes while prioritizing privacy and speed.

- **[Fireflies.ai](https://fireflies.ai/)**  
  Powerful AI meeting assistant with strong search, CRM integrations, conversation intelligence, sentiment analysis, and team collaboration features.

- **[Otter.ai](https://otter.ai/)**  
  One of the most widely used AI note-takers. Offers real-time transcription, speaker identification, automated summaries, and collaboration tools.

### Advanced & Specialized Platforms

- **[tl;dv](https://tldv.io/)**  
  AI meeting recorder with smart clips, summaries, and strong sales/team collaboration features.

- **[MeetGeek](https://www.meetgeek.ai/)**  
  AI meeting assistant focused on insights, templates, and team knowledge sharing.

**Other notable mentions**: Read AI, Avoma, Notta, and integrated solutions like Microsoft Copilot for Teams or Zoom AI Companion.

## Open-Source GitHub Projects

### Dedicated AI Meeting Notes & Transcription Projects

- **[Meetily](https://github.com/Zackriya-Solutions/meetily)**  
  Top privacy-first, fully self-hosted AI meeting assistant. Features fast local transcription (Whisper/Parakeet), speaker diarization, and Ollama-powered summarization. Runs 100% locally on macOS, Windows, and Linux with no data leaving your machine.

- **[Char (anarlog)](https://github.com/fastrepl/anarlog)**  
  Open-source Granola alternative. AI notetaking app designed for meetings (online or offline). Combines your memos with AI to generate personalized summaries. Fully offline-capable with Ollama or LM Studio.

- **[Pensieve](https://github.com/lukasbach/pensieve)**  
  Local-only desktop app for recording meetings or memos. Uses Whisper for transcription and local LLMs for summarization. Keeps everything private on your device.

- **[Ownscribe](https://github.com/paberr/ownscribe)**  
  Local-first CLI for meeting transcription and summarization. Records system audio, transcribes with WhisperX, and generates structured notes using local LLMs (Phi-4-mini or Ollama).

- **[Meetscribe](https://github.com/pretyflaco/meetscribe)**  
  Fully local meeting transcription tool with speaker diarization, AI-generated summaries (via Ollama), and professional PDF output.

- **[AI-Powered-Meeting-Summarizer](https://github.com/AlexisBalayre/AI-Powered-Meeting-Summarizer)**  
  Simple Gradio web app that transcribes audio using Whisper and generates concise summaries with Ollama.

- **[Summeet](https://github.com/lyzgeorge/summeet)**  
  FastAPI + Vue-based tool that converts audio recordings into structured summaries with speaker identification and action items.

- **[Meeting-Transcriber](https://github.com/pasrom/meeting-transcriber)**  
  Native macOS menu bar app for automatic meeting detection, on-device transcription, and summarization.

### Additional Strong Open-Source Options

- **Whisper-based projects** — Many community forks and wrappers for real-time transcription and summarization.
- **[MasterTranscriber](https://github.com/LoveIiei/MasterTranscriber)** — Windows desktop app for real-time transcription, translation, and summarization.
- Obsidian plugins for AI meeting notes (record + transcribe + summarize directly in your vault).

**Frameworks for building custom agents**: Combine **Whisper** (or WhisperX/Faster-Whisper), **Ollama**, **LangGraph** / **CrewAI** for multi-agent pipelines (transcription agent + summarization agent + action item agent). Use local vector stores for searchable meeting history.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Always verify data privacy (especially for sensitive meetings), security, and compliance when using any tool or self-hosting open-source projects.
- AI-generated meeting notes are powerful productivity tools but **not substitutes** for human review, especially for legal, medical, or high-stakes decisions.

---

**Made for professionals, teams, and developers seeking better meeting productivity.**  
Let's make meeting notes smarter, faster, and fully private.

## Star History

<a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-AI-Meeting-Notes&type=date&legend=bottom-right">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-AI-Meeting-Notes&type=date&theme=dark&legend=bottom-right" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-AI-Meeting-Notes&type=date&legend=bottom-right" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-AI-Meeting-Notes&type=date&legend=bottom-right" />
 </picture>
</a>


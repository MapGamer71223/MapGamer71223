# Punyansh Sharma

Building AI-driven automation systems focused on content pipelines, retrieval systems, and real-time media generation.

---

# Projects

## AI Shorts Pipeline

End-to-end automated YouTube Shorts generation system built around:
- LLM-generated scripts
- semantic clip retrieval
- TTS + Whisper alignment
- FFmpeg rendering
- word-level subtitle synchronization

Core pipeline architecture: :contentReference[oaicite:0]{index=0}

```text
topic
  ↓
LLM script generation
  ↓
script scoring + refinement
  ↓
semantic clip retrieval (CLIP + FAISS)
  ↓
TTS generation
  ↓
Whisper word alignment
  ↓
ASS subtitle generation
  ↓
FFmpeg rendering
  ↓
final vertical short
````

### System Components

#### Script Engine

Generates and scores viral-style short-form scripts using local LLMs with:

* batch generation
* hook mutation
* script validation
* metadata generation
* retention-focused scoring

Implemented in `script_engine.py` and GUI orchestration layer.

---

#### CLIP + FAISS Retrieval Engine

Semantic moment-level video retrieval system using:

* CLIP embeddings
* FAISS indexing
* motion scoring
* category-aware ranking
* multi-frame analysis

Supports intelligent clip selection instead of random stock footage.

```text
script line
   ↓
CLIP text embedding
   ↓
FAISS similarity search
   ↓
moment-level retrieval
   ↓
motion/category reranking
   ↓
best matching segment
```

Implemented in:

* `build_index.py`
* `clip_engine.py`
* `clip_sorter.py`

---

#### Rendering Pipeline

Custom FFmpeg-based render engine with:

* TTS-driven pacing
* exact subtitle synchronization
* automatic clip timing
* vertical formatting
* ASS subtitle compositing

```text
audio timing = master timeline
clip durations follow speech
captions follow Whisper timestamps
```

Implemented in `part3.py`. 

---

#### TTS + Alignment

Voice synthesis pipeline using:

* Edge TTS / Tortoise TTS
* Whisper forced alignment
* per-word timestamps
* subtitle timing generation

Implemented in `tts_engine.py`. 

---

## Alice — Voice AI Assistant

Desktop AI assistant focused on low-latency interaction and voice-driven workflows.

```text
mic input
   ↓
speech processing
   ↓
LLM inference
   ↓
TTS generation
   ↓
animated response
```

Built using:

* Python
* PyQt5
* local LLMs
* TTS systems
* Unity integration

Focus:

* real-time interaction
* modular architecture
* voice-first UX

---

# Engineering Focus

```text
INPUT → PROCESS → OUTPUT

Everything is a pipeline.

- modular stages
- deterministic flow
- automation-first design
- semantic retrieval
- low manual overhead
```

---

# Stack

```yaml
languages:
  - Python
  - Kotlin
  - C++

ai:
  - LLM APIs
  - Whisper
  - CLIP
  - FAISS
  - TTS systems

systems:
  - FFmpeg
  - PyQt5
  - REST APIs
  - Async pipelines

data:
  - SQLite
  - PostgreSQL

tools:
  - Git
  - Linux
```

---

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=MapGamer71223&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117"/>

<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MapGamer71223&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117"/>

</div>
```

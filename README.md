````md
# Punyansh Sharma

Building AI systems focused on:
- real-time voice interaction
- semantic retrieval
- automation pipelines
- AI-driven media generation

---

# Projects

## Alice — AI Voice Assistant

Real-time desktop AI assistant built around:
- streaming LLM interaction
- semantic memory retrieval
- voice-first UX
- local AI inference
- desktop automation

Core architecture built using:
- PyQt5
- Ollama
- Piper TTS
- Whisper-style voice pipelines
- SQLite + vector memory

System design references:


---

## Alice System Architecture

```text
microphone input
        ↓
speech recognition
        ↓
input filtering + intent routing
        ↓
semantic memory retrieval
        ↓
LLM streaming inference
        ↓
emotion detection
        ↓
Piper TTS synthesis
        ↓
animated HUD response
````

---

## Alice Core Systems

### Streaming LLM Engine

Alice uses local LLM inference through Ollama with:

* token streaming
* low-latency response generation
* asynchronous worker threads
* conversational memory injection

```text
user input
   ↓
memory context injection
   ↓
Ollama streaming
   ↓
partial token emission
   ↓
real-time HUD update
```

Implemented in:

* `ai_connector.py`
* `alice_hud.py`

---

### Semantic Memory System

Custom long-term memory engine using:

* SQLite persistence
* SentenceTransformers embeddings
* FAISS / HNSW retrieval
* semantic recall
* contextual conversation injection

```text
conversation
      ↓
embedding generation
      ↓
vector indexing
      ↓
semantic retrieval
      ↓
memory-enhanced prompting
```

Features:

* persistent memory database
* similarity search
* GPU-accelerated FAISS support
* background indexing
* contextual recall

Implemented in `memory_manager.py`.



---

### Voice + TTS Pipeline

Real-time voice interaction system using:

* Piper TTS
* threaded playback
* streaming response handling
* interruption support
* emotion-aware synthesis pipeline

```text
LLM response
    ↓
emotion analysis
    ↓
Piper synthesis
    ↓
audio playback
    ↓
HUD animation sync
```

Features:

* low-latency synthesis
* playback interruption
* cached audio generation
* threaded voice queue system

Implemented in:

* `tts_engine.py`
* `utils.py`



---

### Intent + Action Engine

Voice-controlled desktop automation layer supporting:

* application launching
* browser control
* search automation
* system monitoring
* keyboard/mouse automation
* window management

```text
voice command
      ↓
intent classification
      ↓
action routing
      ↓
desktop automation
```

Capabilities:

* open applications
* control windows
* system statistics
* volume control
* screenshots
* web automation

Implemented in:

* `intent_engine.py`
* `assistant_actions.py`



---

### HUD Interface

Custom futuristic PyQt5 HUD interface with:

* animated avatar rendering
* live transcript display
* streaming responses
* speaking state visualization
* emotion-reactive UI
* voice activity animation

```text
AI state
   ↓
HUD renderer
   ↓
animated avatar
   ↓
real-time feedback
```

Built using:

* PyQt5
* QThreads
* animated GIF rendering
* asynchronous event systems

Implemented in:

* `alice_hud.py`
* `main.py`

---

# AI Shorts Pipeline

Automated short-form video generation system using:

* LLM-generated scripts
* semantic clip retrieval
* CLIP + FAISS indexing
* Whisper alignment
* FFmpeg rendering

```text
topic
  ↓
script generation
  ↓
semantic clip retrieval
  ↓
TTS generation
  ↓
subtitle alignment
  ↓
FFmpeg rendering
  ↓
final short
```

Core systems:

* CLIP embeddings
* FAISS retrieval
* automated pacing
* subtitle synchronization
* rendering orchestration

---

# Engineering Focus

```text
INPUT → PROCESS → OUTPUT

Everything is a pipeline.

- modular systems
- semantic retrieval
- local-first AI
- automation-first design
- real-time interaction
- low-latency workflows
```

---

# Stack

```yaml
languages:
  - Python
  - Kotlin
  - C++

ai:
  - Ollama
  - Whisper
  - CLIP
  - FAISS
  - SentenceTransformers
  - Piper TTS

frameworks:
  - PyQt5
  - PyTorch

systems:
  - FFmpeg
  - SQLite
  - REST APIs
  - Async pipelines

tools:
  - Git
  - Linux
  - Windows automation
```

---

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=MapGamer71223&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117"/>

<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MapGamer71223&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117"/>

</div>
````

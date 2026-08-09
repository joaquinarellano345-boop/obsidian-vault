---
type: community
cohesion: 0.08
members: 38
---

# test_transcribe.py

**Cohesion:** 0.08 - loosely connected
**Members:** 38 nodes

## Members
- [[Build a domain hint for Whisper from god nodes extracted from the corpus.      F]] - rationale - graphify/transcribe.py
- [[Download audio-only stream from a URL using yt-dlp.      Returns the path to the]] - rationale - graphify/transcribe.py
- [[Empty god_nodes returns fallback prompt.]] - rationale - tests/test_transcribe.py
- [[Empty input returns empty list without error.]] - rationale - tests/test_transcribe.py
- [[GRAPHIFY_WHISPER_PROMPT env var short-circuits LLM call.]] - rationale - tests/test_transcribe.py
- [[If transcript already exists, transcribe() returns cached path without running W]] - rationale - tests/test_transcribe.py
- [[ImportError propagates when faster_whisper is not installed.]] - rationale - tests/test_transcribe.py
- [[Nodes missing 'label' keys are safely skipped.]] - rationale - tests/test_transcribe.py
- [[Path_54]] - code
- [[Return True if the string looks like a URL rather than a file path.]] - rationale - graphify/transcribe.py
- [[Returns a topic-based prompt from god node labels — no LLM call.]] - rationale - tests/test_transcribe.py
- [[Tests for graphify.transcribe — videoaudio transcription support.]] - rationale - tests/test_transcribe.py
- [[Transcribe a list of videoaudio files or URLs, return paths to transcript .txt]] - rationale - graphify/transcribe.py
- [[Transcribe a videoaudio file or URL to a .txt transcript.      If video_path is]] - rationale - graphify/transcribe.py
- [[_get_whisper()]] - code - graphify/transcribe.py
- [[_get_yt_dlp()]] - code - graphify/transcribe.py
- [[_model_name()]] - code - graphify/transcribe.py
- [[build_whisper_prompt()]] - code - graphify/transcribe.py
- [[download_audio()]] - code - graphify/transcribe.py
- [[force=True re-transcribes even when cache exists.]] - rationale - tests/test_transcribe.py
- [[is_url()]] - code - graphify/transcribe.py
- [[test_build_whisper_prompt_env_override()]] - code - tests/test_transcribe.py
- [[test_build_whisper_prompt_no_nodes()]] - code - tests/test_transcribe.py
- [[test_build_whisper_prompt_nodes_without_labels()]] - code - tests/test_transcribe.py
- [[test_build_whisper_prompt_returns_topic_string()]] - code - tests/test_transcribe.py
- [[test_transcribe.py]] - code - tests/test_transcribe.py
- [[test_transcribe_all_empty()]] - code - tests/test_transcribe.py
- [[test_transcribe_all_skips_failed()]] - code - tests/test_transcribe.py
- [[test_transcribe_all_uses_cache()]] - code - tests/test_transcribe.py
- [[test_transcribe_force_reruns()]] - code - tests/test_transcribe.py
- [[test_transcribe_missing_faster_whisper()]] - code - tests/test_transcribe.py
- [[test_transcribe_uses_cache()]] - code - tests/test_transcribe.py
- [[test_video_extensions_set()]] - code - tests/test_transcribe.py
- [[transcribe()]] - code - graphify/transcribe.py
- [[transcribe.py]] - code - graphify/transcribe.py
- [[transcribe_all()]] - code - graphify/transcribe.py
- [[transcribe_all() returns cached paths for already-transcribed files.]] - rationale - tests/test_transcribe.py
- [[transcribe_all() warns and skips files that fail to transcribe.]] - rationale - tests/test_transcribe.py

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/test_transcribepy
SORT file.name ASC
```

## Connections to other communities
- 2 edges to [[_COMMUNITY_ingest.py]]
- 2 edges to [[_COMMUNITY_validate_url]]
- 1 edge to [[_COMMUNITY_paths.py]]
- 1 edge to [[_COMMUNITY_cli.py]]

## Top bridge nodes
- [[transcribe.py]] - degree 12, connects to 3 communities
- [[download_audio()]] - degree 8, connects to 2 communities
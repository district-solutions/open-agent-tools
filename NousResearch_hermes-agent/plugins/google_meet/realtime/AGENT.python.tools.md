# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/plugins/google_meet/realtime/openai_client.py

Prompts

```
['send text to the OpenAI Realtime API and write the audio PCM response to a file', 'open a WebSocket connection to the OpenAI Realtime API with a configured voice and model', 'cancel an in-flight audio response on the OpenAI Realtime WebSocket to stop generation immediately', 'run a file-based JSONL queue loop that processes text-to-speech entries one at a time until stopped', 'read and parse the JSONL queue file to get pending text-to-speech entries with ids and text']
```

Usage

```
{'speak_text_to_audio': 'send text to the OpenAI Realtime API and write the audio PCM response to a file', 'connect_realtime_session': 'open a WebSocket connection to the OpenAI Realtime API with a configured voice and model', 'cancel_response_barge_in': 'cancel an in-flight audio response on the OpenAI Realtime WebSocket to stop generation immediately', 'run_speaker_queue_loop': 'run a file-based JSONL queue loop that processes text-to-speech entries one at a time until stopped', 'read_speaker_queue': 'read and parse the JSONL queue file to get pending text-to-speech entries with ids and text'}
```

